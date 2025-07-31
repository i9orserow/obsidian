Неделя 1: Введение в Docker

Цель: Понять, что такое Docker и зачем он нужен.

    Что такое Docker, контейнеры и образы

    Установка Docker (Fedora: sudo dnf install docker)

    Запуск и остановка контейнеров (docker run, docker stop)

    Основные команды: docker ps, docker images, docker rm, docker rmi

Практика:

    Запусти простой контейнер: docker run hello-world

    Попробуй контейнер с Ubuntu: docker run -it ubuntu bash
    Неделя 2: Работа с образами

Цель: Понять, как создавать и использовать Docker-образы.

    Docker Hub и как искать образы

    Команда docker pull, docker build, docker tag, docker push

    Написание простого Dockerfile

Практика:

    Собери образ с Nginx или Python

    Попробуй запустить свой образ

Неделя 3: Docker Compose

Цель: Управление многоконтейнерными приложениями.

    Что такое docker-compose

    Структура docker-compose.yml

    Команды: docker-compose up, down, logs, exec

Практика:

    Запусти проект с PostgreSQL + Adminer

    Попробуй связку Node.js + MongoDB

Неделя 4: Работа с томами и сетями

Цель: Хранение данных и настройка сетевого взаимодействия.

    Томы (volumes) — docker volume create, -v

    Сети (networks) — docker network create, bridge, host

    Переменные окружения (environment:)

Практика:

    Создай контейнер с сохранением данных в volume

    Настрой два контейнера, чтобы они "видели" друг друга

Неделя 5: Продвинутые темы

Цель: Углубление и подготовка к продакшн.

    Оптимизация Dockerfile

    Multi-stage build

    Безопасность контейнеров

    Работа с Docker Registry

Практика:

    Собери и оптимизируй образ для небольшого Flask-приложения

    Разверни локальный Docker Registry

