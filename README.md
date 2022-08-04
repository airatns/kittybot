# Kittybot

Telegram-бот, который на запрос пользователя отправляет картинки с котиками. Если доступ к кошкам невозможен, отправляются картинки с собаками.

<img width="414" alt="cats" src="https://user-images.githubusercontent.com/96816183/182933247-c835bc25-66d3-459b-96cb-342e2ee08a69.png">

## **Стек технологий**

Python, Django, Telegram Bot

## **Как запустить проект:**

Клонировать репозиторий и перейти в него в командной строке:

>*git clone git@github.com:airatns/kittybot.git*

Cоздать и активировать виртуальное окружение:

>*python -m venv env*

>*source env/scripts/activate*

Установить зависимости из файла requirements.txt:

>*python -m pip install --upgrade pip*

>*pip install -r requirements.txt*

Прописать параметры окружения в файле .env:

* TELEGRAM_TOKEN

Запустить проект:

>*python kittybot.py*
