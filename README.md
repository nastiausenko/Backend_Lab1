# Лабораторна робота №1

## Запуск проєкту

> NOTE: Для запуску проєкту на комп'ютері повинні бути встановлені [Docker](https://www.docker.com/) та docker-compose

1. Склонуйте репозиторій, використовуючи команду:

```
git clone https://github.com/nastiausenko/Backend_Lab1.git
```

2. Введіть наступну команду для створення образу (image):

```
docker build -t backend .
```
3. Для запуску контейнера Docker введіть команду:

```
docker-compose up
```
Після запуску проєкт буде доступний за посиланням [http://localhost:8080/healthcheck](http://localhost:8080/healthcheck)

### [Посилання на деплой](https://backend-lab1-1-c1dx.onrender.com/healthcheck)