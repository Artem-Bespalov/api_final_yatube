<h1 align="center">Проект «API для Yatube»</h1>

<h4>API для Yatube представляет собой проект социальной сети в которой реализованы следующие возможности: публикация записей, комментирование записей, а так же подписка или отписка от авторов.</h4>

### Стек технологий:
![python version](https://img.shields.io/badge/Python-3.7.9-green)
![django version](https://img.shields.io/badge/Django-2.2.16-green)
![django rest framework](https://img.shields.io/badge/DjangoRestFramework-3.12.4-green)
![Html](https://img.shields.io/badge/HTML-green)
![CSS](https://img.shields.io/badge/CSS-green)
![Bootstrap](https://img.shields.io/badge/Bootstrap-green)

### Запуск проекта в dev-режиме:
1. Склонировать репозиторий:
```
git clone https://github.com/Artem-Bespalov/api_final_yatube
```
2. Установить и активировать виртуальное окружение:
```
python -m venv venv
```
```
source venv/Scripts/activate
```
3. Установить зависимости из файла requirements.txt:
```
pip install -r requirements.txt
```
4. Выполнить миграции:
```
python manage.py migrate
```
5. Запустить сервер:
```
python manage.py runserver
```

### Примеры запросов к API:
* ```api/v1/posts/``` - Получение публикаций (GET)
* ```api/v1/posts/{id}/``` - Получение публикации (GET)
* ```api/v1/posts/{post_id}/comments/``` - Получение комментариев (GET)
* ```api/v1/posts/{post_id}/comments/{id}/``` - Получение комментария (GET)
* ```api/v1/groups/``` - Получение списка сообществ (GET)
* ```api/v1/groups/{id}/``` - Получение информации о сообществе (GET)
* ```api/v1/follow/``` - Получение информации о подписках (GET)

### Автор проекта:
<a href="https://github.com/Artem-Bespalov">Артем Беспалов</a>















