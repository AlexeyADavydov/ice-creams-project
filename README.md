## Дни рождения друзей

### Описание

Проект представляет собой неинтерактивный каталог с мороженым и реализован в первую очередь для тестирования функционала верстки Bootstrap.

Проект позволяет:
- посмотреть имеющийся каталог мороженного в ассортименте.

Фронтенд приложения реализован на Bootstrap, а бэкенд разработан на Django. Проект запущен на виртуальном удаленном сервере.


### Стек технологий

Python, Django, SQLite, Pillow, Bootstrap, CSS, HTML, Django Debug Toolbar, Fixtures, Nginx, Certbot, Gunicorn

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/yandex-praktikum/ice-creams-project.git
```

```
cd anfisa_for_friends
```

Cоздать и активировать виртуальное окружение:

Windows
```
python -m venv venv
source venv/Scripts/activate
```
Linux/macOS
```
python3 -m venv venv
source venv/bin/activate
```

Обновить PIP

Windows
```
python -m pip install --upgrade pip
```
Linux/macOS
```
python3 -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Выполнить миграции:

Windows
```
python manage.py makemigrations
python manage.py migrate
```

Linux/macOS
```
python3 manage.py makemigrations
python3 manage.py migrate
```

Запустить проект:

Windows
```
python manage.py runserver
```

Linux/macOS
```
python3 manage.py runserver
```


### Работающий результат

[ice-creams.alexeyadavydov.com](https://ice-creams.alexeyadavydov.com/)

### Автор проекта (бэкенд и деплой)

[AlexeyADavydov](https://github.com/AlexeyADavydov/)