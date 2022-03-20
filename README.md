# Yatube API
- Социальная сеть для блогеров.

# Установка
 **Как развернуть проект на локальной машине**:
 
Клонировать репозиторий и перейти в него в командной строке:


    git clone https://github.com/carden-code/api_final_yatube
    cd api_final_yatube
Cоздать и активировать виртуальное окружение:


    python3 -m venv venv
    source venv/bin/activate
    python3 -m pip install --upgrade pip

Установить зависимости из файла requirements.txt:

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
# Эндпоинты
- Все доступные эндпоинты и документация с примерами доступны:
	- http://127.0.0.1:8000/redoc/

# Лицензия
Этот проект лицензируется в соответствии с лицензией MIT

![](https://miro.medium.com/max/156/1*A0rVKDO9tEFamc-Gqt7oEA.png "1")