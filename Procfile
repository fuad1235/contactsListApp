release: python manage.py makemigrations
release: python manage.py migrate

web: python manage.py runserver

web: gunicorn contactsapi.wsgi
