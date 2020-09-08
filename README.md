# django-async-importer

django-import-export is a Django application and library for importing and exporting data with included admin integration.

Features:

- support CSV
- admin integration for importing
- preview import changes
- admin integration for exporting
- export data respecting admin filters

# Example App

```bash
cd demo
./manage.py makemigrations
./manage.py migrate
./manage.py createsuperuser
./manage.py loaddata category book
./manage.py runserver
```
