# InkSpot
A web app for drawing and sharing art straight from your web browser.


## Instructions
01. clone this repo
02. install Python 3.11.4
03. setup a Python virtual environment:
  1. on Windows, execute `python -m venv venv`
  2. on Linux, execute `python3 -m venv venv`
04. activate the virtual environment:
  1. on Windows, execute `.\venv\Scripts\activate`
  2. on Linux, execute `./env/bin/activate`
05. execute `pip install -r requirements.txt` to install the project dependencies
06. execute `cd InkSpot` to switch to the Django project folder
07. execute `python manage.py migrate` to apply migrations to the database
08. exeucte `python manage.py createsuperuser` to create a super user account
09. execute `python manage.py runserver` to start the web server
10. visit http://localhost:8000 in your web browser
