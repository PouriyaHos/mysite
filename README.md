django-polls
============
Django tutorial polls app



--Requirements :

Python 3.7.3

Django 2.2

Pip 19.1




--Install dependencies:

pip install -r requirements.txt




_______________________________________________________________________________________________________________________
Content 

1. What is this app used for?  
This app uses for Polls systems or as a Polls App ,
which is through that you can Add ,Delete ,Edit Questions and Answers with different users and admins with special or unic 
username and password 

2. What does one need to install before running the app, what are the requirements?
Python    
Django
One software as a code editor


3. How to install all the Python packages from the requirements.txt (we know that at least one is listed in there)?  
forexample for installing an astroid we should type it in command :

>>pip install astroid


4. How to run the app locally? 
with this command you can run it locally :
>>py manage.py runserver

and it will give you an address to watch it in your browser something like this :

127.0.0.1:8000


5. Which are some relevant URLs for the app? Eg. how to access the admin interface?  
URL for Admin :
127.0.0.1:8000/admin/



6. A simple example of the app’s functionality. Eg. how to add a new Polls and Questions? How can I submit an answer to a question? 

from django.contrib import admin

from .models import Question

admin.site.register(Question)


for polls we should run this command: 
py manage.py makemigrations polls
