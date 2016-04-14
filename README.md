#Pre-requisites for Django 1.9

Pip
Virtualenv (optional, but recommended)
Python 3
Django 1.9


#Creating a virtual enviroment

$ cd any_folder_you_want

$ virtualenv /folder/for/virtual_enviroment

#Install Django

$ pip install django==1.9

Create a django project 

$ django-admin.py startproject project_name

Rename the root project folder "/project_name" to src 

Inside the SRC folder create a bash script to run the project

exec ./manage.py runserver 0.0.0.0:<your_port>

save it as runserver in the same dir as manage.py

chmod +x runserver

and run it as

./runserver


# Django

