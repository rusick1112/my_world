# Стек
[![Python version](https://img.shields.io/static/v1?label=Python&logo=python&message=3.12.7&color=blue)](https://www.python.org/)
[![Python web framework](https://img.shields.io/static/v1?label=Django&logo=django&message=5.0.6&color=blue)](https://www.djangoproject.com/)
[![Bootstrap](https://img.shields.io/static/v1?label=Bootstrap&logo=bootstrap&message=5.3.2&color=purple)](https://getbootstrap.com/)


## AuthCatalog
Данный проект представляет собой веб-приложение c возможностью авторизации через сторонние сервисы с помощью OAuth 2.0, а также с небольшой сервис с товарами. Проект создан с помощью Django Framework, при использовании REST архитерктуры построения приложения, Bootstrap. 📝
---

## Описание проекта
Цель проекта — разработка веб-приложения, с использованием авторизации с помощью сторонних сервисов при помощи OAuth 2.0 и сервиса с товарами для покупки.

---

## Основные возможности

- **Авторизация через сторонние сервисы** Github и Google. ✅
- **Просмотр товаров** широкий выбор товаров. 👩‍🎓🧑‍💻
- **Гибкая система управления тестами** для преподавателей и администраторов. 🔧

---

## Используемые технологии

- **Язык программирования:** Python 🐍
- **Фреймворк:** Django Framework 🌐
- **База данных:** SQLite (с возможностью перехода на другие СУБД) 🗂️

### Обоснование стека

**Полнота:** встроенная админ-панель, ORM для работы с базами данных и готовая конфигурация проекта.
**Быстрая разработка:** следование принципу DRY (Don't Repeat Yourself) ускоряет процесс разработки и упрощает поддержку кода.
**Гибкость:** структура проекта упрощает организацию кода и масштабирование приложения. 📏


---

## ⚙️ Установка и запуск

### 1️⃣ Клонирование репозитория

```bash
git clone https://github.com/rusick1112/my_world.git
cd my_world
```

### 2️⃣ Настройка виртуального окружения

```bash
python -m venv .venv
source venv/bin/activate  # Для Linux/macOS
# или
.venv\Scripts\activate    # Для Windows
```

### 3️⃣ Установка зависимостей

```bash
pip install -r requirement.txt
```

### 4️⃣ Миграция базы данных

```bash
python manage.py migrate
```

### 5️⃣ Запуск сервера разработки

```bash
python manage.py runserver
```

Приложение будет доступно по адресу: [http://127.0.0.1:8000/](http://127.0.0.1:8000/) 🌍

---

## Фото проекта

![главная страница](https://github.com/rusick1112/my_world/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202025-02-11%20144351.png?raw=true)
![OAuth2.0](https://github.com/rusick1112/my_world/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202025-02-11%20145419.png?raw=true)
