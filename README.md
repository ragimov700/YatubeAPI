<h1 align="center">Yatube API</h1>

**YatubeAPI** — RESTful API для проекта [Yatube](https://github.com/ragimov700/Yatube).

---

### Возможности

- Создавать посты
- Комментировать
- Подписываться на авторов

Дополнительные возможности описаны в redoc-документации `/redoc`

### Технологии
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
![DjangoREST](https://img.shields.io/badge/DJANGO-REST-ff1709?style=for-the-badge&logo=django&logoColor=white&color=ff1709&labelColor=gray)

### Установка:

#### 1. Клонируйте репозиторий

```
git clone https://github.com/ragimov700/YatubeAPI.git
```

#### 2. Создайте и активируйте виртуальное окружение

```
python -m venv venv
source venv/bin/activate
```

#### 3. Установите зависимости

```
pip install -r requirements.txt
```

#### 4. Примените миграции и запустите проект

```
python yatube_api/manage.py migrate
python yatube_api/manage.py runserver
```
После чего проект будет доступен по адресу http://localhost:8000/

---
<h5 align="center">Автор проекта: <a href="https://github.com/ragimov700">Sherif Ragimov</a></h5>
