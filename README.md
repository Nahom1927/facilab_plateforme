Introduction
Hello everyone ! My name is Élodie Riou. I'm 31 years old and I finished the first year at Holberton Schoo: THE FOUNDATIONS.

The aim of the project was to create a web application to put into contact people with difficulties with FabLab who can provide them with solutions to make their lives easier.

This project was initiate by the association May’Human Lab of Laval in Mayenne(53).

The objectives
The objective of the portfolio project was to create an MVP (Most Viable Product) during 3 weeks. But not only. We had to create a landing page, a demo on Youtube, a blog post and a wonderful README.

The challenges
The challenges of my project was to create a simple interface, easier to use. Next, it was the implementation of Django.

I choose Django because is popular and offer tons of libraries and tools for common use cases (ORM, authentication, HTML templating, URL routing, forms, view layers, model layers). Then, Django offers a fully-featured web interface for the admin panel. Finally, there is a very good documentation with example code which is very helpful in building some features.

The links
I would like to share with you, some production about FACIL@B PLATFORM :

The demo live
The landing page
The blog post
And about me :

My Linkedin
Installation
FACIL@B PLATFORM has been programming on Ubuntu 20.04.4 LTS and the technology following :

Language Python 3.8.10
$ sudo apt update
$ sudo apt install python3.8
Framework Django 4.0.5
$ pip install Django
Templating Jinja2 3.1.2
$ pip install Jinja2
Usage
Some commands are essential working with a django project :

1. Generate the code base
$ django-admin startproject <name_project>
2. Create the app
$ python3 manage.py startapp <name_application>
3. Create the database
$ python3 manage.py migrate
This command generate a file db.sqlite3 by default. You can change the database if you want.

4. Apply modification to your database
$ python3 manage.py makemigrations
$ python3 manage.py migrate
5. Run the local server
$ python3 manage.py runserver

