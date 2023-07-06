# REST API приложения для управления ToDo списками

## Приложение позволяет осуществлять:

* регистрацию/аутентификацию пользователей
* CRUD-операции со списками
* CRUD-операции с элементами списков

## В ходе создания приложения были получены навыки:

* использования подходов Чистой Архитектуры в построении структуры приложения
* разработки веб-приложения на Go с дизайном REST API
* конфигурирования приложения с помощью библиотеки spf13/viper и работы с переменными окружения
* работы с фреймворком gin-gonic/gin
* работы с Postgresql (запуск из Docker) с использованием библиотеки sqlx
* регистрации и аутентификации, работы с JWT

## Запуск приложения
```azure
docker-compose up todo-app
```