## ЗАПУСК ПРОЕКТА ЧЕРЕЗ "manage.py"

Введи последовательно все нижеперечисленные команды:

`python3 -m venv venv`

`source venv/bin/activate`

`pip install -r requirements.txt`

`python3 manage.py migrate`

`python3 manage.py runserver`

Проект запущен.

---

## СОЗДАНИЕ СУПЕРЮЗЕРА ДЛЯ ДОСТУПА К АДМИНИСТРАТИВНОЙ ПАНЕЛИ DJANGO

После ввода нижепредставленной команды нужно вести логин, почту (по необходимости) и пароль дважды:

`python3 manage.py createsuperuser`

Админка доступна по url: http://127.0.0.1:8000/admin/

