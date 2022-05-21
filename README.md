# docker-command-utils

## Create a Postgres database

> docker run --name postgres-db -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres


## Run postgres command in terminal

> docker exec -it name_container psql -U user -W postgres

## List process in port 5432 - Mac

> sudo lsof -i :5432
