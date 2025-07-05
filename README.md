Проект создавался как замена ушедшим из России сервисам по типу - Trello(Atlassian), youtrack, kaiten.
Так как проект содержит информацию о работе в компании прикладываю скриншоты дизайна, которые не содержат конфиденциальную информацию и в точности показывают его возможности - https://github.com/Fairfay/Yourtask_promo

Проект был разработан с нуля, начиная от проектирования его архитектуры и бд, до микросервисов и поддержки websocket.

Подключены healthcheck, проект обернут в docker-compose, используется ci-cd, поддерживаются websocket и подключены service worker, используются jwt токены и django-axes в качестве дополнительной системы безопасности, файлы хранятся в облачном хранилище s3, вход в приложение возможен через yandex_id, telegram_auth, логин/пароль используются уведомления как пуш, так и в телеграм и на почту, система версионирования - gitlab.
Бот в тг - @SmarTaskBot.

Проект входит в реестр российского ПО.

Основной стек технологий:
Django
Poetry
Pytest
Unittest
API - Django rest framework
Uvicorn
Websocket - Django channel
Postgres
Redis
Celery
Flower
JWT
AWS S3 Ростелеком
Telegram api
Yandex api
Swagger
Docker
Docker-compose
Gitlab container registry
Sentry
React
Redux
D3
Ckeditor5
Dhtmlx
Oauth
Nginx - gateway
Axios
