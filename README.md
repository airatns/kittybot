# @newkittybot

Telegram-бот, который на запрос пользователя отправляет картинки с котиками. Если доступ к API Кошек невозможен, отправляются картинки с API Собак.

<img width="414" alt="cats" src="https://user-images.githubusercontent.com/96816183/182935591-18de4c93-7392-44c3-84d4-1fbb96610f20.png">

## **Стек технологий**

Python, Django, Telegram Bot

## **Как запустить проект:**

Клонировать репозиторий и перейти в него в командной строке:

>*git clone git@github.com:airatns/kittybot.git*

Cоздать и активировать виртуальное окружение:

>*python -m venv env* \
>*source env/scripts/activate*

Установить зависимости из файла requirements.txt:

>*python -m pip install --upgrade pip* \
>*pip install -r requirements.txt*

Прописать параметры окружения в файле .env:

* TELEGRAM_TOKEN

Запустить проект:

>*python kittybot.py*
