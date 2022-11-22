Проект «API для Yatube»

http://127.0.0.1:8000/redoc/ Документация для API Yatube

API для Yatube представляет собой проект социальной сети в которой реализованы следующие возможности: публикация записей, комментирование записей, а так же подписка или отписка от авторов.

Установка:

1. Скопируйте репозиторий в свою папку: https://github.com/Artem-Bespalov/api_final_yatube.git

2. Установите виртуальное окружение: python -m venv venv

3. Активируйте виртуальное окружение: source venv/Scripts/activate

4. Установите зависимости из requirements.txt: pip install -r requirements.txt

5. Выполните миграции: python manage.py migrate

6. Запустите сервер: python manage.py runserver
