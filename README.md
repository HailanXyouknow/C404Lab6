# CMPUT404 Lab4

## Instructions
See [this page](https://uofa-cmput404.github.io/lab-4-django.html)

## To Run

```bash
python manage.py runserver
```

## For Heroku

```
python manage.py makemigration 
git push heroku main
heroku run [--app APPNAME] python manage.py migrate
heroku run [--app APPNAME] python manage.py createsuperuser
```
