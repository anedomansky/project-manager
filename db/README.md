# Proma (DB)

## Build image

docker build -t proma-db .

## See all images

docker images

## Start container

docker run -d -p 5432:5432 --name proma-db proma-db

docker run -d --rm -p 5432:5432 --name proma-db proma-db

## See all running containers

docker ps

## Show logs

docker logs proma-db

## Connect to container

docker exec -it proma-db bash

## Connect to database

psql -h localhost -d proma -U dev
