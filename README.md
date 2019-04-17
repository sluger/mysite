# mysite
Django Getting Started

## Prerequisites
Install Python 3.7, pip, and Django 2.2

## Local Development

Create db and migrate
```bash
python manage.py migrate
```

Create admin user
```bash
python manage.py createsuperuser
```

Start dev server
```bash
python manage.py runserver
```

## Add some data
Use one of the following options to add some data:

a) Try out API and insert some data: 
https://docs.djangoproject.com/en/2.2/intro/tutorial02/#playing-with-the-api

b) Use the admin interface and insert some data:
http://127.0.0.1:8000/admin/

Checkout the app at http://127.0.0.1:8000/polls/