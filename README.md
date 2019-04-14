# Django Docker
Django docker boilerplate with database.



Make migrations:

```bash
docker-compose run --rm django_app python manage.py makemigrations
docker-compose run --rm django_app python manage.py migrate
docker-compose run --rm django_app python manage.py createsuperuser
```
RUN
```
docker-compose up
```