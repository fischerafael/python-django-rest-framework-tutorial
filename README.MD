1 - Crete virtual environment
py -m venv env

2 - Install django
pip install django

3 - Install django-rest-framework
pip install djangorestframework

4 - Setup Project
django-admin startproject tutorial .
cd tutorial
django-admin startapp quickstart
]

6 - Super User
python manage.py createsuperuser --email admin@example.com --username admin
admin@example.com
123456
