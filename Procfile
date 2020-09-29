release: python manage.py migrate
release: python manage.py collectstatic
web: gunicorn ecommerce.wsgi:application
