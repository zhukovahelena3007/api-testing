**Тестирование API** 

**REST collection**

*Тестирование REST API интернет-магазина DemoShopping по Swagger-документации.*
[![Run in Postman](https://www.postman.com/elenazhuzhu07-9576735/workspace/elena-s-workspace/collection/58407221-860cb050-769e-4ec4-ab10-9d4294207ae2?action=share&creator=58407221&active-environment=58407221-cce06f22-2a7e-4d6e-9d7e-d7a6d8267f6b)](https://postman.com)


Что было сделано:

• Структура: Создана коллекция DemoShopping с логическим разделением на папки (Users, Products, Cart) и понятным неймингом запросов под конкретные проверки.

• Работа с методами и авторизацией: Настроены CRUD-запросы (в PUT исключен id из тела во избежание ошибки сервера) и авторизация по токену для доступа к методам корзины.

• Переменные окружения (QA): Настроены baseUrl, id и токен авторизации (назван key вместо token для сохранения публичности коллекции в Postman).

• Автотесты (JS): Для всех методов Products написаны скрипты, проверяющие статус-коды, типы данных и изменения значений в теле ответа, а также время ответа сервера.
Инструменты: Postman, JavaScript (Chai), Swagger, REST API.
