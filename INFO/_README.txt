Приклади REST-запитів:

Отримання всіх даних
GET
http://localhost:8082/api/v1.0/contacts

Отримання даних за id
GET
http://localhost:8082/api/v1.0/contacts/2

Створення даних
POST
http://localhost:8082/api/v1.0/contacts

Налаштування в Postman: Body, raw, JSON.

{
    "id": 5,
    "name": "John",
    "number": "5558719879"
}

Оновлення даних за id
PUT
http://localhost:8082/api/v1.0/contacts/2

Налаштування в Postman: Body, raw, JSON.

{
    "number": "5555619951"
}

Видалення даних за id
DELETE
http://localhost:8082/api/v1.0/contacts/3



