release: python manage.py makemigrations --no-input
release: python manage.py migrate --no-input

web: web: gunicorn MyBank.MyBank.wsgi
