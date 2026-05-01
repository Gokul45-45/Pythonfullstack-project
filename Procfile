web: gunicorn lms_project.wsgi
web: python manage.py migrate && python manage.py collectstatic --noinput && gunicorn lms_project.wsgi --bind 0.0.0.0:$PORT