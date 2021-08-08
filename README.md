# Финальный проект - API "YATUBE"

## Стек:
> Python, Djando, DRF

## Описание
Данное API позволяет использовать следующий функционал:

Посты
+ Получать все посты
+ Создавать новые и редактировать

Группы
+ Получать список групп
+ Создавать новые группы

Комментарии
+ Получать список всех комментариев поста
+ Создавать новые комментарии

Подписка
+ Пользователи могут получать список своих подписчиков
+ Пользователи могут подписываться и отписываться от других пользователей

## Докуметация по API
Более подробное описание API можно получить по адресу: http://localhost:8000/redoc/

## Установка
Клонировать репозиторий:
$ git clone https://github.com/AltBansha/api_final_yatube.git

## Создать виртуальное окружение:
$ python -m venv venv

## Установить зависимости:
$ pip install -r requirements.txt

## Сделать миграции
$ python manage.py makemigrations и $ python manage.py migrate
