# serverless-link-shortener
## Сервис по сокращению ссылок на python3.8 и node12 с использованием API шлюза, базы данных, хранилища файлов и облачных функций от Яндекса.
## Описание базы данных в файл links.sql
## Описание апи шлюза в файле gateway.conf. Надо подставить свои значения
## Описание функции на питоне в файле index.py. Эндпоинт - index.handler. Пример енв для работы с базой в файле .env.example.
## Описание функции на ноде в файле index.js. Зависимости в файле package-lock.json (unquote и ydb-sdk.) Эндпоинт - index.handler. Пример енв для работы с базой в файле .env.example.
## Описание корневого файла в index.html. Необходимо создать свое ведро (bucket) для управления файлами.
## Т.к. в ноде присутсвуют заивисимости, то для загрузки исходного кода в функцию необходимо загрузить архив через вкладку object storage и указать свой bucket и архив.
