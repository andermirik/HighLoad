## Лабораторная работа 5

Подключить кафку к разработанному приложению https://spring.io/projects/spring-kafka

_Перереквизиты:
Поднять зукпиер, поднять три брокера, нужные топики, настроить репликацию_

Реализовать
- [ ]  паттерн saga, для операций, которые в первой лабе были помечены @Transactional https://microservices.io/patterns/data/saga.html

- [ ]  модуль слушающий два топика

`app-high-throughput-topic`
топик в который пишут ваши приложения свои метрики со spring-boot-actuator'а https://docs.spring.io/spring-boot/docs/current/reference/html/actuator.html

`app-safe-topic`
топик в который пишутся данные об изменении вашей корневой сущности (корневая, которая включает в себя и не включается в другие сущности)

Данный модуль должен писать полученные значения в соответствующий индекс в эластике(предполагается, что для этих индексов есть дашборд в кибане)

Требуется доказать, что ваша конфигурация топиков, продьюсеров и консьюмеров/стримов/коннекторов идеально подходит для поставленной задачи