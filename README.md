# yamdb_final
yamdb_final

API для YaMDB. YaMDb содержит отзывы (Review) пользователей на произведения (Titles). Произведения делятся на категории: «Фильмы» и «Музыка». Список категорий может расширить админ. У произведений есть название, описание, жанр, год создания и категория.

Файл .env должен лежать в корневой папке. В себе он содержит данные для подключения базы данных и секретный ключ. 

Запустить программу: docker-compose up

Создать суперпользователя: docker-compose exec web python manage.py createsuperuser

Заполнить базу данных: django-admin loaddata fixtures.json

Ознакомиться с документацией: http://127.0.0.1/redoc/

Адрес: http://178.154.195.129/api/v1/

![example workflow](https://github.com/dayterr/yamdb_final/actions/workflows/yamdb_workflow.yml/badge.svg)