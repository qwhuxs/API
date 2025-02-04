# RESTful API на FastAPI

## Опис
Цей API підтримує CRUD операції:  
- **GET /items** – отримати всі елементи  
- **POST /items** – створити новий елемент  
- **PATCH /items/{item_id}** – оновити елемент  
- **DELETE /items/{item_id}** – видалити елемент  

## Запуск
1. Встановити залежності:  
   ```bash
   pip install fastapi uvicorn

2. Запустити сервер:
   uvicorn main.main:app --reload

3. Документація доступна за адресами:
  Swagger: http://127.0.0.1:8000/docs
  ReDoc: http://127.0.0.1:8000/redoc

# FastAPI Items API

Цей проект створений для керування елементами через REST API.

# Авторизація та ролі

API використовує JWT-авторизацію для перевірки доступу до ендпоінтів.

# Ролі користувачів:

- **User – може переглядати список елементів та отримувати окремі елементи.

- **Admin – може створювати, оновлювати та видаляти елементи.

## Документація API
Повний опис endpoints доступний за посиланням:
[FastAPI Items API Documentation](https://documenter.getpostman.com/view/41782468/2sAYX5M3j8)
