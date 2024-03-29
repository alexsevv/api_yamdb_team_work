# API для Yatube


## Описание
Проект позволяет авторизованным пользователям ставить оценки разным произведениям, оставлять комментарии, отзывы к ним.
Проект реализован на [Django REST framework](https://www.django-rest-framework.org/).


## Как запустить проект:

1. Kлонируем репозиторий:
```
git clone 
```
2. Cоздаем виртуальную среду:
```
python3 -m venv venv
```
3. Активируем виртуальную среду:
```
source venv/bin/activate
```
4. Устанавливаем зависимости:
```
pip install -r requirements.txt
```
5. Запустите dev-сервер:

```
python manage.py runserver
```

## Документация к API:

Здесь описаны все доступные ендпоинты и примеры запросов к ним:
http://127.0.0.1:8000/redoc/



## Авторы
- [Александр Матияка](https://github.com/alexsevv)
- [Максим Краев](https://github.com/loony-m)
- [Алексей Алексеев](https://github.com/Litandepython)