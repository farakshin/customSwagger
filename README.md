# <img src="https://raw.githubusercontent.com/swagger-api/swagger.io/wordpress/images/assets/SWU-logo-clr.png" width="300">

## Установка
- раскапуйте архив
- перейдите в директорию customSwagger через командную строку (терминал)
- выполните скрипт ```python3 cors_server.py 8080``` (либо выберите другой свободный порт) чтобы запустить локальный сервер

## Использование
- разместите спецификацию (.yml, .json) в папку customSwagger
- в браузере откройте [localhost:8080](http://localhost:8080)
- в интерфейсе вместо https://petstore.swagger.io/v2/swagger.json заполните ```http://localhost:8080/файл_спецификации``` (пример ```http://localhost:8080/test.yml```) и нажмите "Explore"

## Возможности
- просмотр полносью развернутой древовидной модели запросов/ответов 
- просмотр табличного описания
- копирование таблицы в буфер обмена
