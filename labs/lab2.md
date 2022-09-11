# Лабораторная работа 2

https://microservices.io/

Декомпозировать на микросервисы систему из лабораторной работы 1.

- [ ] Микросервисы должны  регистрироваться в `Eureka` https://spring.io/projects/spring-cloud-netflix
- [ ] Микросервисы должны подтягивать конфигурацию из `Config-Server` https://spring.io/projects/spring-cloud-config
- [ ] Микросервисы должны быть доступны через `Spring Gateway`  https://spring.io/projects/spring-cloud-gateway
- [ ] Для взаимодействия между микросервисами использовать `Feign Client`
- [ ] Внедрить `Circuit Breaker` https://cloud.spring.io/spring-cloud-netflix/multi/multi__circuit_breaker_hystrix_clients.html
- [ ] Решить проблему с авторизацией между микросервисами
- [ ] Минимум один микросервис должен быть написан с использованием `Reactor` и `r2dbc`
- [ ] Минимум один микросервис должен быть написан с использованием `Reactor` и `spring-data-jpa`
- [ ] Минимум один микросервис должен использовать только `jdbc`
