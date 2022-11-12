```mermaid

sequenceDiagram
    participant frontend
    participant notification facade
    participant query (Redis)
    participant notification processing
    participant files facade
    participant files processing
    participant MinIO
    
    frontend ->>notification facade: get unread notifications
    notification facade -->> frontend: notifications
    
    frontend ->>notification facade: connect to websocket
    
    frontend ->> files facade: upload file
    files facade ->> files processing: upload file
    files processing ->> MinIO: upload file
    MinIO -->> files processing: Done
    
    files processing ->> notification processing : notification file uploaded
    notification processing ->> query (Redis): notification file uploaded
    query (Redis) ->> notification facade: notification file uploaded
    notification facade ->> frontend: notification file uploaded via websocket
    
    files processing -> files facade: 200 OK
    
    files facade -->> frontend: 200 OK
    
    
```
