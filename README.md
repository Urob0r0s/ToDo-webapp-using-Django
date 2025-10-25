# ToDo Web Application

Простое и эффективное веб-приложение для управления задачами, построенное на Django. Позволяет пользователям создавать, отслеживать и удалять свои ежедневные задачи.

## 🚀 Функционал

*   **Полный CRUD для задач:** Создавайте, просматривайте, редактируйте и удаляйте задачи.
*   **Отметка о выполнении:** Легко отмечайте задачи как выполненные.
*   **Чистый интерфейс:** Простой и интуитивно понятный пользовательский интерфейс для продуктивной работы.
*   **Сортировка по статусу:** Просматривайте все, активные или завершенные задачи.

## 🛠️ Технологии

*   **Backend:** Django (Python)
*   **Frontend:** HTML, CSS
*   **База данных:** SQLite (по умолчанию, легко меняется на PostgreSQL и др.)

## 📦 Установка и Запуск

Следуйте этим шагам, чтобы запустить проект локально.

1.  **Клонируйте репозиторий:**
    ```bash
    git clone https://github.com/Urob0r0s/ToDo-webapp-using-Django.git
    cd ToDo-webapp-using-Django
    ```

2.  **Создайте и активируйте виртуальное окружение (рекомендуется):**
    ```bash
    python -m venv venv
    # Для Windows:
    venv\Scripts\activate
    # Для Linux/macOS:
    source venv/bin/activate
    ```

3.  **Установите зависимости:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Примените миграции базы данных:**
    ```bash
    cd .\todo_site\
    python manage.py migrate
    ```

5.  **Запустите сервер для разработки:**
    ```bash
    python manage.py runserver
    ```

6.  **Откройте приложение:**
    Перейдите по адресу [http://127.0.0.1:8000](http://127.0.0.1:8000) в вашем браузере.

## 📁 Структура Проекта

# ToDo Web Application

![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=green)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)

Простое и эффективное веб-приложение для управления задачами, построенное на Django. Позволяет пользователям создавать, отслеживать и удалять свои ежедневные задачи.

## 🚀 Функционал

*   **Полный CRUD для задач:** Создавайте, просматривайте, редактируйте и удаляйте задачи
*   **Отметка о выполнении:** Легко отмечайте задачи как выполненные
*   **Чистый интерфейс:** Простой и интуитивно понятный пользовательский интерфейс
*   **Сортировка по статусу:** Просматривайте все, активные или завершенные задачи
*   **Поиск и фильтрация:** Быстрый поиск по задачам

## 🛠️ Технологии

*   **Backend:** Django 4.2+ (Python)
*   **Frontend:** HTML, CSS, Bootstrap
*   **База данных:** SQLite (по умолчанию)
*   **Аутентификация:** Django Session Authentication

## 📦 Установка и Запуск

Следуйте этим шагам, чтобы запустить проект локально.

### Предварительные требования

*   Python 3.8+
*   pip (менеджер пакетов Python)

### Шаги установки

1.  **Клонируйте репозиторий:**
    ```bash
    git clone https://github.com/Urob0r0s/ToDo-webapp-using-Django.git
    cd ToDo-webapp-using-Django
    ```

2.  **Создайте и активируйте виртуальное окружение:**
    ```bash
    python -m venv venv
    # Для Windows:
    venv\Scripts\activate
    # Для Linux/macOS:
    source venv/bin/activate
    ```

3.  **Установите зависимости:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Примените миграции базы данных:**
    ```bash
    python manage.py migrate
    ```

5.  **Создайте суперпользователя (опционально):**
    ```bash
    python manage.py createsuperuser
    ```

6.  **Запустите сервер для разработки:**
    ```bash
    python manage.py runserver
    ```

7.  **Откройте приложение:**
    Перейдите по адресу [http://127.0.0.1:8000](http://127.0.0.1:8000) в вашем браузере.

## 📁 Структура Проекта

```plaintext
ToDo-webapp-using-Django/
│
├── todo/                          # Основное приложение
│   ├── migrations/                # Файлы миграций базы данных
│   ├── templates/todo/            # HTML шаблоны
│   │   ├── base.html             # Базовый шаблон
│   │   ├── index.html            # Главная страница
│   │   └── task_confirm_delete.html # Подтверждение удаления
│   ├── __init__.py
│   ├── admin.py                  # Настройки админ-панели
│   ├── apps.py                   # Конфигурация приложения
│   ├── models.py                 # Модели данных (Task)
│   ├── tests.py                  # Тесты
│   ├── urls.py                   # Маршруты приложения
│   ├── views.py                  # Представления (логика)
│   └── forms.py                  # Формы Django
│
├── todoproject/                   # Настройки проекта
│   ├── __init__.py
│   ├── asgi.py                   # ASGI конфигурация
│   ├── settings.py               # Основные настройки
│   ├── urls.py                   # Корневые маршруты
│   └── wsgi.py                   # WSGI конфигурация
│
├── static/                       # Статические файлы (CSS, JS, изображения)
│   ├── css/
│   └── js/
│
├── media/                        # Медиа файлы (загружаемые пользователями)
│
├── requirements.txt              # Зависимости проекта
├── manage.py                     # Утилита управления Django
├── db.sqlite3                    # База данных SQLite (создается автоматически)
└── README.md                     # Документация проекта



## 🤝 Вклад в Проект

Вклады приветствуются! Если у вас есть предложения по улучшению, пожалуйста, создайте fork репозитория и отправьте pull request.

1.  Сделайте fork проекта.
2.  Создайте ветку для вашей фичи (`git checkout -b feature/AmazingFeature`).
3.  Закоммитьте ваши изменения (`git commit -m 'Add some AmazingFeature'`).
4.  Запушите ветку (`git push origin feature/AmazingFeature`).
5.  Откройте pull request.

