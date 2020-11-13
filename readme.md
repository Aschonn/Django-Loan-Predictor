# Loan Approval/Disapproval Predictor

Motivation:

This application predicts if your loan will be approved or not. This Was created using Django Framework and Machine Learning 🤖👋

Dependencies:

    I used python 3.7 but anything over 3.7 will work.
    All the related dependencies are in the requirements.txt


Required Knowledge:

    Django (Framework)
    Python (Language)
    Postgresql (Database)


    ### used anaconda as my virutalenv of choice but feel free to use what feels comfortable.


How to run:
Anaconda Enviroment Installation:

    https://docs.anaconda.com/anaconda/install/


Setup database:
Enter In Database:

    In the settings.py file enter in credentials for postgresql or sqlite3

Migration Models/Tables To Database:

    python manage.py makemigrations
    python manage.py migrate

Create a superuser (access admin page):

    python manage.py createsuperuser
    Answer all questions
