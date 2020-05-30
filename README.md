# Full-Stack-React-Django

## url

[Yoytube tutorial Full Stack React &amp; Django](https://www.youtube.com/watch?v=Uyei2iDA4Hs&amp;list=PLillGF-RfqbbRA-CIUxlxkUpbq0IFkX60&amp;index=1)

[django REST framework](https://www.django-rest-framework.org/)

## os environment

ubuntu20.04

## install command

```
# virtual
pythopn3 -m venv venv

# start

.venv/bin/activate

pip freeze

pip install django djangorestframework django-rest-knox

```

## generate django project

```
django-admin startproject leadmanager

```

## generate django app leads

```
cd leadmanager

python manage.py startapp leads
```
## start development server

```
python manage.py runserver
```

## django make model Tenplatge

```
python manage.py makemigrations
```

## django make database

```
python manage.py migrate
```
