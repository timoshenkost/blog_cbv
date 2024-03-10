# Django CBV Blog
Блог, разработанный с использованием Django фреймворка и широко использующий Class-Based Views (CBV).

## Функциональность
- Регистрация пользователей с помощью электронной почты и пароля
- Возможность авторизации для зарегистрированных пользователей
- Создание, редактирование и удаление постов блога
- Отображение списка всех постов с возможностью поиска и фильтрации
- Комментирование и оценки постов
- Поддержка пагинации для длинных списков постов
- Автоматическое форматирование текста с использованием Markdown
- Загрузка изображений для постов
- Поиска по тегам
- Поддержка ролей пользователей (администратор, автор, читатель, гость)
- Использование Class-Based Views для управления различными функциями приложения

## Технологии
- Python
- Django
- HTML/CSS
- JavaScript
- Bootstrap
- База данных SQLite

# Django Blog
Блог, разработанный с использованием Django фреймворка.

Запуск приложения
------
1. Склонируйте репозиторий:
```
git clone https://github.com/timoshenkost/blog_cbv
```

2. Перейдите в директорию проекта:
```
cd blog_cbv
```

3. Создайте виртуальное окружение и активируйте его:
```
python -m venv venv
source venv/bin/activate  # для Linux/Mac
venv\Scripts\activate  # для Windows
```

4. Установите зависимости:
```
pip install -r requirements.txt
```

5. Создайте в корне файл `.env` и запишите следующие поля:
```
SECRET_KEY = Ваш SECRET_KEY
RECAPTCHA_PUBLIC_KEY = '6LddLC0pAAAAAG2u0P97oeEzmCjufurYgBxKdG1z'
RECAPTCHA_PRIVATE_KEY = '6LddLC0pAAAAAI7ElDhOTY3ho7WUyvxh-ViyBkO8'
```

6. Выполните миграции базы данных:
```
python manage.py migrate
```

7. Для использования админ панели cоздайте суперпользователя:
```
python manage.py createsuperuser
```

8. Запустите сервер:
```
python manage.py runserver
```

Проект будет доступен по адресу http://localhost:8000/

