# Docker Flask Demo

Мини‑проект, показывающий контейнеризацию простого Python‑приложения

## Стек
- Docker
- Python
- Flask

## Структура проекта
- Dockerfile
- app.py

## Как запустить

### 1. Собрать образ
docker build -t flask-demo .

### 2. Запустить контейнер
docker run -p 8080:80 flask-demo

После запуска открой в браузере:
http://localhost:8080
