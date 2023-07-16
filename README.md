### Описание:

# Социальная сеть yatube.

Телеграм-бот для отслеживания статуса проверки домашней работы на Яндекс.Практикум.

### Технологии

Python 3.7

python-telegram-bot 13.7


### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/Sarugot/homework_bot.git
```

```
cd homework_bot
```

Cоздать и активировать виртуальное окружение:

```
python -m venv env
```

```
source env/bin/activate
```

Установить зависимости из файла requirements.txt:

```
python -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Указать необходимые ключи в .env файле:

```
Токен профиля на Яндекс.Практикуме
Токен телеграм-бота
ID в телеграме
```

Выполнить миграции:

```
python manage.py migrate
```

Запустить проект:

```
python manage.py runserver
```
