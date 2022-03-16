pip install pipenv // is like npm
pipenv install django==2.1// install  django 

pipenv shell // activate environment
django-admin startproject test_project .// create new project

python manage.py runserver// running Django’s local web server

control + c and exit // stop the server and exit env

python manage.py startapp pages // create app

////////////////////app File structure/////////////
admin.py is a configuration file for the built-in Django Admin app
apps.py is a configuration file for the app itself
migrations/ keeps track of any changes to our models.py file so our database and
models.py stay in sync
models.py is where we define our database models, which Django automatically
translates into database tables
tests.py is for our app-specific tests
views.py is where we handle the request/response logic for our web app

// http models
URL -> View -> Model (typically) -> Template