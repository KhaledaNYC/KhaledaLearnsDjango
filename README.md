# KhaledaLearnsDjango

Lil' Cheatsheet

$ django-admin startproject yourprojectname <br>
$ python manage.py runserver <br>
$ python manage.py startapp appname<br>
$ python manage.py migrate<br>
$ python manage.py makemigrations appname<br>
$ python manage.py shell<br>
$ python manage.py createsuperuser<br>

-------------------------------------------------------
Models

from django.db import models

class ModelName(models.Model):<br>
  name_of_string_field = models.CharField(max_length=100) <br>
  name_of_number_field = models.IntegerField(max_digits=10,<br>
  decimal_places=2) <br>
  name_of_float_field = models.FloatField() <br>
  
More field types
https://docs.djangoproject.com/en/1.9/ref/models/fields/

Views - CRUD actions

Template - Views
