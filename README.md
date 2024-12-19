# effectivebackend

## Website template for backend development learning (Django)

This repository contains a simple book-tracking website with a local library, connected database, and admin panel.

Built following the tutorial from:
https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django

---

## First lab features:

### Covered Sections:
* 1: Local Library website
* 2: Building the skeleton
* 3: Working with models
* 4: Django Admin Interface

### Outcomes:
* A template (skeleton) website with a connected database
* Data models for population
* Admin panel for data management
* Superuser account for admin access

## Required Tools:
* Python (3.12.8)
* Poetry (1.8.5)

## Installation and Launch:

1. Clone the repository:
   ```bash
   git clone https://github.com/tintanaa/effectivebackend
   cd effectivebackend/'feature1/website_creation_preparation'
   ```

2. Install dependencies:
   ```bash
   poetry install
   ```

3. Navigate to the required directory:
   ```bash
   cd ./locallibrary/
   ```

4. Create the `.env` file:
   ```bash
   echo SECRET_KEY= > .env
   echo DEBUG= >> .env
   ```

5. Open the `.env` file and input the values for `SECRET_KEY` and `DEBUG`:
   ```bash
   SECRET_KEY=<secret-key-value>
   DEBUG=<debug-value>
   ```

6. Apply database migrations:
   ```bash
   poetry run python manage.py makemigrations
   poetry run python manage.py migrate
   ```

7. Run server:
   ```bash
   poetry run python3 manage.py runserver
   ```

---

## Шаблон сайта для обучения backend разработке (Django)

Этот репозиторий содержит простой сайт для учёта книг, локальную библиотеку, подключённую базу данных и админпанель.

Создан по учебному примеру с сайта:
https://developer.mozilla.org/ru/docs/Learn/Server-side/Django

---

## First lab features:

### Пройдены разделы:
* 1: Локальная библиотека
* 2: Создание скелета
* 3: Работа с моделями
* 4: Административная панель Django

### Результаты:
* Шаблон (скелет) сайта с подключённой базой данных
* Модели данных для заполнения
* Админка для управления данными
* Суперпользователь для доступа к админпанели

## Необходимые инструменты:
* Python (3.12.8)
* Poetry (1.8.5)

## Установка и запуск:

1. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/tintanaa/effectivebackend
   cd effectivebackend/'feature1/website_creation_preparation'
   ```

2. Установите зависимости:
   ```bash
   poetry install
   ```

3. Переместитесь в нужный каталог:
   ```bash
   cd ./locallibrary/
   ```

4. Создайте файл `.env`:
   ```bash
   echo SECRET_KEY= > .env
   echo DEBUG= >> .env
   ```

5. Откройте файл `.env` и введите значения для `SECRET_KEY` и `DEBUG`:
   ```bash
   SECRET_KEY=<secret-key-value>
   DEBUG=<debug-value>
   ```

6. Примените миграции к базе данных:
   ```bash
   poetry run python manage.py makemigrations
   poetry run python manage.py migrate
   ```

7. Запустите сервер:
   ```bash
   poetry run python manage.py runserver
   ```
