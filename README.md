## Методы
1. **Создание пользователя**
   - **URL**: `/user`
   - **Метод**: POST
   - **Тело запроса**:
     ```json
     {
       "username": "example",
       "email": "example@example.com",
       "password": "password123"
     }
     ```

2. **Обновление информации пользователя**
   - **URL**: `/user/{id}`
   - **Метод**: PUT
   - **Тело запроса**:
     ```json
     {
       "username": "newUsername",
       "email": "newEmail@example.com"
     }
     ```

3. **Удаление пользователя**
   - **URL**: `/user/{id}`
   - **Метод**: DELETE

4. **Авторизация пользователя**
   - **URL**: `/user/auth`
   - **Метод**: POST
   - **Тело запроса**:
     ```json
     {
       "username": "example",
       "password": "password123"
     }
     ```

5. **Получение информации о пользователе**
   - **URL**: `/user/{id}`
   - **Метод**: GET

---