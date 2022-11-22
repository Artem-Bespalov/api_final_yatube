Проект «API для Yatube»

http://127.0.0.1:8000/redoc/ Документация для API Yatube

API для Yatube представляет собой проект социальной сети в которой реализованы следующие возможности: публикация записей, комментирование записей, а так же подписка или отписка от авторов.

Установка:

Скопируйте репозиторий в свою папку: https://github.com/Artem-Bespalov/api_final_yatube.git

Установите виртуальное окружение: python -m venv venv

Активируйте виртуальное окружение: source venv/Scripts/activate

Установите зависимости из requirements.txt: pip install -r requirements.txt

Выполните миграции: python manage.py migrate

Запустите сервер: python manage.py runserver

Использованные технологии:

Python 3.7.9
Django 2.2.16
djangorestframework 3.12.4

Примеры запросов к API:
Получение публикаций (GET): http://127.0.0.1:8000/api/v1/posts/

Получение публикации (GET): http://127.0.0.1:8000/api/v1/posts/{id}/

Получение комментариев (GET): http://127.0.0.1:8000/api/v1/posts/{post_id}/comments/

Получение комментария (GET): http://127.0.0.1:8000/api/v1/posts/{post_id}/comments/{id}/

Список сообществ (GET): http://127.0.0.1:8000/api/v1/groups/

Информация о сообществе (GET): http://127.0.0.1:8000/api/v1/groups/{id}/

Подписки (GET): http://127.0.0.1:8000/api/v1/follow/
