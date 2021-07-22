web: gunicorn run:app --log-file -
migrate: python manage.py db migrate
upgrade: python manage.py db upgrade
worker: python mqtt.py