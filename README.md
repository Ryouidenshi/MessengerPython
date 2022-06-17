- Реализация на питоне
![image](https://user-images.githubusercontent.com/55030527/174362559-d3330db0-6db3-48bb-a218-3b596c654247.png)
- Основной сервис - rest api на fastapi
![image](https://user-images.githubusercontent.com/55030527/174363447-f6e1434d-62c3-458f-a215-50e9f694e58d.png)
Основная логика приложения соединяется с интерфейсом, используя фреймворк  Fastapi
- Работа с БД через sqlalchemy, миграции через alembic
![image](https://user-images.githubusercontent.com/55030527/174374524-295abba0-11a2-40bd-9dcf-97710bf61cfc.png)
![image](https://user-images.githubusercontent.com/55030527/174376981-e3238d3a-21a0-469c-9519-acf6ce4bd442.png)
- Аутентификация пользователей через JWT token
![image](https://user-images.githubusercontent.com/55030527/174380309-dc2dacd0-783e-41d4-b46c-12538bdc544e.png)
- Отложенные задачи, реализованные с помощью celery
![image](https://user-images.githubusercontent.com/55030527/174381996-4c2374b7-edc4-46f8-a024-8f7092200dd2.png)
Пример
- Вебсокет и отправка через него обновлений о сообщениях пользователя
![image](https://user-images.githubusercontent.com/55030527/174387051-f0087683-875f-41ff-9e1e-29c1e8c43f30.png)
![image](https://user-images.githubusercontent.com/55030527/174387293-73a81970-81c7-4ba3-9abc-370024b7cfdd.png)
- Отдельный rest api сервис, который вызывается в каких-то методах основного апи (как, например, выделение метаданных из текста сообщения)
используется в соединениях сервисных процессов и интерфейсов
