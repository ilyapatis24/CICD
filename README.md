# Домашнее задание к лекции «CI/CD»
## Задание

- Развернуть собственное flask приложение из домашнего задания лекции “Flask” на Heroku (или другом) сервере.
- Настроить процессы CI/CD для запуска тестов и сборки после каждого коммита на основной ветке.

К проверке прислать git репозиторий и ссылку на работающий web сервис.
 
<h2 align="center">Сборка образа</h2>

```docker build -t ilya/app:1 .```

<h2 align="center">Запуск контейнера</h2>

```docker run --name flask_app -d -p 5000:5000 ilya/app:1```
