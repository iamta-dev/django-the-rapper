# django-the-rapper

## [Python] Django 101 
### Install
```
python3 -m venv env
source env/bin/activate

# Escape from venv
deactivate

# Create project & app
pip install -r requirement.txt
django-admin startproject PROJECT-NAME
python manage.py start app APP-NAME
python manage.py createsuperuser
```

### Commands 
```
# Run server
python manage.py runserver

# Create migrations
python manage.py makemigrations

# Run migration
python manage.py migrate

# Collect static files
python manage.py collectstatic
```

### Other Postgres DB setup  
```
sudo -u postgres psql

postgres=# CREATE DATABASE myproject;
postgres=# CREATE USER myprojectuser WITH PASSWORD 'password';

```