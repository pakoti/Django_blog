# Django_blog
A simple Blog Wirtten In Django 3.1.0

This reprository is for New and biggeners who want to learn aout django3 by doing simple project like make a simple blog.

before starting you should learn basic HTML/CSS,Not so much,only basic things like tags and how to make simple front-end.

1.Installing python virtual Environment:
#pipenv install django~=3.1.0
#pipenv shell

2.Starting A new Project in the virtual Environment:
#django-admin startproject config .

3.Starting A new Application within the Django:
#python manage.py startapp blog

4.Migrating The Database:
#python manage.py migrate

5.We should add The blog Appliction to settings.py:

INSTALLED_APPS = [
    'django.contrib.admin',
    'django.contrib.auth',
    'django.contrib.contenttypes',
    'django.contrib.sessions',
    'django.contrib.messages',
    'django.contrib.staticfiles',
    'blog' #newly installed app
]

6.Migrate the Database:
#python manage.py migrate

7.Run the Server To check if everything is ok:
#python manage.py runserver

8.Now let's define a Database Model for our blog:
A





















