# Ex02 Django ORM Web Application
## Date: 

## AIM
To develop a Django application to store and retrieve data from a Football Players database using Object Relational Mapping(ORM).

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
Execute Django admin and create 10 Football players

## PROGRAM
model.py
from django.db import models
from django.contrib import admin
class football_Player (models.Model):
    name=models.CharField(max_length=100)
    height = models.IntegerField()
    age=models.IntegerField()
    weight=models.IntegerField()
    experience = models.IntegerField()
admin.py
class Playeradmin(admin.ModelAdmin):
    list_display=('name','height','age','weight','experience')

## OUTPUT
![Screenshot 2024-01-02 032743](https://github.com/nareshofficial/ORM/assets/155141830/ed91029b-67c1-4eb1-9002-8ac5ba8e1458)



## RESULT
Thus the program for creating a database using ORM hass been executed successfully
