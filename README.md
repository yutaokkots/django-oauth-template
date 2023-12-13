# Django OAuth boilerplate Repo

A boilerplate Django (back-end only) repository containing Auth modules. 

Contains a number of popular Authentication/Authorization-related Python packages to allow easier project set-up. 
Ideal for usage with a separate front-end.

Please refer to individual dependency documentation for creating and using API endpoints, and the views associated with their packages.

## Installed Dependencies

| | Purpose | Type | Installation | Documentation |
|--|--|--|--|--|
|djangorestframework |For Restful API endpoints in Django|API|% pip install djangorestframework |https://pypi.org/project/djangorestframework/|
|allauth|For third-party OAuth|Auth|% pip install allauth|https://docs.allauth.org/en/latest/installation/quickstart.html|
|dj-rest-auth|For Authentication REST endpoints|Auth|% pip install dj-rest-auth |https://dj-rest-auth.readthedocs.io/en/latest/installation.html#registration-optional|
|djangorestframework-simplejwt|For JSON-web token creation and validation|Auth|% pip install djangorestframework-simplejwt|https://django-rest-framework-simplejwt.readthedocs.io/en/latest/getting_started.html#installation|
|django-cors-headers|For enabling cross-origin resource sharing|CORS|% pip install django-cors-headers|https://pypi.org/project/django-cors-headers/|
|psycopg2|For PostgresQL interface|Database|% pip install psycopg2|https://pypi.org/project/psycopg2/|
|django-environ|For using the environmental variables|ENV|% pip install django-environ|https://django-environ.readthedocs.io/en/latest/install.html|
|Pylint-Django|For linting Python Code|Code Format|% pip install pylint pylint-django |https://pypi.org/project/pylint-django/|
|Black|For cleaning up Python formatting|Code Format|% pip install black|https://pypi.org/project/black/|

## Project installation

1. Fork repo

2. % git init -> % git pull

3. Create virtual environment, and activate:
% python3 -m venv .venv
% . .venv/bin/activate

4. install dependencies:
% pip install -r requirements.txt 