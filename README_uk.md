# E - Journal

[![English](https://img.shields.io/badge/Language-English-green)](README_en.md)

## Опис

Цей проект є веб-додатком для ведення журналу, побудований за допомогою Django.


## Встановлення та запуск


1. Клонуйте репозиторій:
   ```bash
   git clone https://github.com/vitaliikovalkovskyi/E-Journal.git

2. Перейдіть в директорію проекту:
   ```bash
   cd E-Journal

3. Створіть віртуальне середовище на потрібному рівні (в корені проекту):
   ```bash
   python -m venv venv

4. Активуйте віртуальне середовище:
   ```bash
   ./Scripts/activate

5. Перейдіть у директорію journal:
   ```bash
   cd journal

6. Встановіть залежності:
   ```bash
   pip install -r requirements.txt

7. Виконайте міграції:
   ```bash
   python manage.py migrate

8. Запустіть сервер
   ```bash
   python manage.py runserver

## Використання
Відкрийте веб-браузер і перейдіть за адресою http://127.0.0.1:8000/ для перегляду додатку.
## Структура проекту
manage.py: Основний файл для управління проектом.
journal/: Головна конфігурація проекту.
journal_app/: Основна логіка додатку.
templates/: HTML-шаблони.
static/: Статичні файли (CSS, JS, зображення).
## Ліцензія
Цей проект ліцензований під ліцензією MIT.
