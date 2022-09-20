
## Base on [Fazt Tutorial](https://www.youtube.com/watch?v=GE0Q8YNKNgs)
### Steps
## Create a virtual environment to isolate the app modules
* Install the need module `pip install virtualenv`
* Create an env `python3 -m virtualenv venv`
## Install django module and framework 
`pip install django djangoframework`
## Create a django project 
`django-admin startproject djangorestapi .`
## Start project
`python manage.py runserver`
## Create a new application
`python3 manage.py startapp projects`
## Configure the app in the django project
`add two new items 'projects' and 'rest_framework' in INSTALLED_APPS at djangorestapi/settings.py`
## Create a data module
`in projects/models.py create a new class with needed structure`
## Create the model migration
* `python3 manage.py makemigrations`
## Create the tables
* `python3 manage.py migrate`

### Deploy project
## Create an account in [dashboard.render](https://dashboard.render.com/)
## Follow the [Guide](https://render.com/docs/deploy-django)
## Create the requirements file 
`pip3 freeze > requirements.txt`