# Система аутентификации

## Установка

### 1. Клонируйте репозиторий
```bash
git clone https://github.com/Bustle101/pract_6.git
cd pract_6
cd auth-system-main
```

### 2. Создайте и активируйте виртуальное окружение
```bash
python -m venv venv
.\venv\Scripts\Activate 

```

### 3. Установите зависимости Python:
```bash
pip install -r requirements.txt
```
2. Примените миграции:
```bash
python manage.py migrate
```

### 4. Создайте суперпользователя
Для доступа к админке создайте суперпользователя:

```bash
python manage.py createsuperuser
```

### 5. Запустите сервер
Запустите сервер разработки:

```bash
python manage.py runserver
```

2. Откройте http://localhost:8000 в браузере

## Административная панель

Административная панель доступна по адресу http://localhost:8000/admin/
Просматривать кэшированные данные (http://localhost:8000/admin/core/cacheddata/)



