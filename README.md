Установка
Клонируем репозиторий на локальную машину:

$ git clone git@github.com:Thx-Phila/api_final_yatube.git

Создаем виртуальное окружение:

$ python -m venv venv

Устанавливаем зависимости:

$ pip install -r requirements.txt

Создание и применение миграций:

$ python manage.py makemigrations и $ python manage.py migrate

Запускаем django сервер:

$ python manage.py runserver

Все готово к использованию API!
