# Chat-application-
## In order to download and run the project ( It is assumed that Python 3 is already installed ):
Install Django and Apps:
```
pip install Django==3.1.4
pip install django-phonenumber-field[phonenumbers]
```
## Needed to create admin account to check the activities of accounts
Change Directory to Django---Hotel-Management-System/HMS and start the Shell:
```
python manage.py createsuperuser
python3 manage.py makemigration
python3 manage.py migrate
```
## Run the server
```
python3 manage.py runserver
```
## How to create Chat room:
1. We need to goto home page and then put any unique chat room name followed by your name then enter.
2. Share this unique code with your other person to enter the the chat room. 

## How to access admin panel:
1. Goto admin login page and put the ID and Password(Default Id: admin, Password: admin)
2. You can check the activities of chat room and also able to modify.
