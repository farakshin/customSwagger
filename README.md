# <img src="https://raw.githubusercontent.com/swagger-api/swagger.io/wordpress/images/assets/SWU-logo-clr.png" width="300">

## Установка
- раскапуйте архив
- перейдите в директорию customSwagger через командную строку (терминал)
- выполните скрипт ```python3 cors_server.py 8080``` (либо выберите другой свободный порт) чтобы запустить локальный сервер

## Использование
- разместить спецификацию (.yml, .json) в папку customSwagger
- в браузере открыть[localhost:8080](localhost:8080)
- в интерфейсе вместо https://petstore.swagger.io/v2/swagger.json заполнить http://localhost:8080/[файл спецификации] (пример http://localhost:8080/test.yml) и нажать "Explore"
