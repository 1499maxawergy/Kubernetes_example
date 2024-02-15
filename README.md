## Практика 8 по дисциплине "Технологии виртуализации клиент-серверных приложений"
Задание:
- Разработать Backend или часть Backend системы с использованием Spring/Spring Boot.
- Система должна иметь сервис авторизации с хранением токенов в RedisDB и минимум 2 сервиса, которые должны общаться между собой с помощью шины сообщений с использованием Kafka.
- Хранение данных должно производиться с помощью СУБД PostgreSQL.
- В качестве API-шлюза к сервисам должен выступать KrakenD.
- Необходимо логировать все обращения к сервисам с помощью Graylog. В логах должны указываться HTTP-метод, URL, IP-адрес отправителя.
- Также необходимо собирать метрики с баз данных с помощью связки
- Prometheus + Grafana, а все транзакции подвергать трассировке с помощью Jaeger. 
