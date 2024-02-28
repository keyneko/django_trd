# django_trd
```bash
python -m pip install Django
django-admin startproject my_bbs

cd my_bbs
python manage.py runserver

python -m django --version


DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'test',
        'USER': 'keyneko',
        'PASSWORD': 'a1234',
        'HOST': '127.0.0.1',
        'PORT': '3306',
    }
}

pip install mysqlclient

python manage.py migrate

python manage.py createsuperuser --username=admin --email=admin@email.com

python manage.py startapp post
```
