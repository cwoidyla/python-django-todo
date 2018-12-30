# python-django-todo

how to install, activate, and deactivate virtualenv
> pip3 install virtualenv
> mkdir django
> cd django
> virtualenv todo # sets up virtual
> cd todo 
> source ./Scripts/activate # activate virtual environment
> deactivate # deactivate virtual environment
> 

how to install django
# when virtualenv is activated, issue the following cmds
> pip3 install django
> django-admin --version # sanity check

how to initiate django project
> mkdir apps
> django-admin startproject todolist
> cd todolist
> python manage.py startapp todos
> python manage.py runserver