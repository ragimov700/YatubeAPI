### Как запустить проект

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/ragimov700/api_final_yatube
```

```
cd api_final_yatube
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

```
source env/bin/activate
```

Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```
### Примеры запросов:
Получить все посты (GET-метод):
```
http://127.0.0.1:8000/api/v1/posts/
```
Получить пост по id (GET-метод):
```
http://127.0.0.1:8000/api/v1/posts/{id}/
```
Получить комментарии к посту (GET-метод):
```
http://127.0.0.1:8000/api/v1/posts/{id}/comments/
```
Получить все группы (GET-метод):
```
http://127.0.0.1:8000/api/v1/groups/
```
### Документация
Полная документация доступна по адресу:
```
http://127.0.0.1:8000/redoc/
```
