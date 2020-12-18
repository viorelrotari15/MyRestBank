release: python manage.py makemigrations --no-input
release: python manage.py migrate --no-input

web: run-program waitress-serve --port=$PORT settings.wsgi:application
