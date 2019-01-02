# python-django-todo

how to install, activate, and deactivate virtualenv
```bash
> pip3 install virtualenv
> mkdir django
> cd django
> virtualenv todo # sets up virtual
> cd todo 
> source ./Scripts/activate # activate virtual environment
> deactivate # deactivate virtual environment
> 
```

how to install django
```bash
# when virtualenv is activated, issue the following cmds
> pip3 install django
> django-admin --version # sanity check
```

how to initiate django project
```bash
> mkdir apps
> django-admin startproject todolist
> cd todolist
> python manage.py startapp todos
> python manage.py runserver
```

how to initiate django database
```bash
> python manage.py migrate # adds django tables to database specified in settings.py
> python manage.py makemigrations todos # adds django table specified in todos/models.py after todos is declared in settings.py
> python manage.py sqlmigrate todos 0001
> python manage.py migrate
```

how to add admin user account
```bash
> python manage.py createsuperuser --username=conrad --email=conrad@gmail.com
> python manage.py runserver
```

how to install additional libraries
```bash
> pip install --upgrade setuptools # makes sure this is up to date
> pip install ez_setup # this is necessary, but for some reason virtualenv excludes it..
> pip install [library]
```
