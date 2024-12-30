# coding-project-template

## Getting started
```
cd server
pip install virtualenv
virtualenv djangoenv
source djangoenv/bin/activate
python3 -m pip install -U -r requirements.txt
```

Migrations:
1. Perform migrations to create necessary tables.
    python3 manage.py makemigrations

1. Run migration to activate models for the app.
    python3 manage.py migrate

1. Start the local development server.
    python3 manage.py runserver