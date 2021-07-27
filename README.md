# Dockerising-DjangoApp
Dockerised a django app with postgresql and rest framework
Dockerised Django App with REST FRAMEWORK CRUD OPERATIONS and POSRGRESQL

To run the code:

//make migrations first

docker-compose run web python manage.py migrate

//then you can directly run docker image

docker-compose up

OR

//build docker image

docker-compose build

//run docker image

docker-compose run
