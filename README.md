# locallibrary
 Django Local Library Tutorial Project

## Create Virtual Environment

`python -m venv .local-library-env`

## Activate Virtual Environment

`.local-library-env\Scripts\activate`

## Install Dependencies

`python -m pip install -r requirements.txt`

## Migrate database

`python manage.py makemigrations`

`python manage.py migrate`

## Create admin

`python manage.py createsuperuser`

*** Add user name, email and password. ***

## Run Django App

`py manage.py runserver`

### Admin pannel

[/admin/](http://localhost:8000/admin/)

### Catalog app

[/catalog/](http://localhost:8000/catalog/)

## Run Django Test Code
python manage.py test catalog.tests
