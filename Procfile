web: python manage.py migrate && rm -rf staticfiles/* && python manage.py collectstatic --noinput && gunicorn todo_project.wsgi