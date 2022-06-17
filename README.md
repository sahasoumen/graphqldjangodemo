# GraphQL DJango API Demo

## All executed commands
### Environment setup
$ source env/bin/activate\
$ pip install django\
$ pip install djangorestframework\
$ pip install graphene-django

### Create Project
$ django-admin startproject graphqldjangodemo

### Configure git
$ cd graphqldjangodemo\
$ git init\
$ echo "# graphqldjangodemo" >> README.md\
$ git add .\
$ git commit -m "Initial commit"\
$ git remote add origin https://github.com/sahasoumen/graphqldjangodemo.git \
$ git branch -M main\
$ git push -u origin main

### Start Server
$ python manage.py runserver

### Create backend
$ django-admin startapp products

### Create Models
$ python manage.py makemigrations\
$ python manage.py migrate


### Reference
https://www.section.io/engineering-education/integrating-graphql-api-in-a-django-application/