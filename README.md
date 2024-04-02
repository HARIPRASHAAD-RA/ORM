# Ex02 Django ORM Web Application
## Date: 02-04-2024

## AIM
To develop a Django application to store and retrieve data from a Book database using Object Relational Mapping(ORM).

## Entity Relationship Diagram

Include your ER diagram here

## DESIGN STEPS

### STEP 1:
Clone the problem from GitHub

### STEP 2:
Create a new app in Django project

### STEP 3:
Enter the code for admin.py and models.py

### STEP 4:
Execute Django admin and create details for 10 books

## PROGRAM
```
from django.db import models
  class Employees(models.Model):
    empid=models.IntegerField()
    empname=models.CharField(max_length=30)
    dept=models.CharField(max_length=20)
    salary=models.FloatField()

from django.contrib import admin
  from .models import Employees
  admin.site.register(Employees)
```
    


## OUTPUT

![image](https://github.com/HARIPRASHAAD-RA/ORM/assets/164654451/105955e9-9462-4c1f-9a7e-a28bccc5f83b)
![image](https://github.com/HARIPRASHAAD-RA/ORM/assets/164654451/19d848c0-e9b0-45da-8b8a-d0022a981f16)




## RESULT
Thus the program for creating a database using ORM hass been executed successfully
