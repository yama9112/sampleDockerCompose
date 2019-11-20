# sampleDockerCompose
## build
docker-compose build

docker-compose up -d

## mysql
docker-compose exec mysql bash

mysql -u user -p test_db

show databases;

## postgres
docker-compose exec postgres bash

psql -U user test_db

\l
