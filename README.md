# docker-command-utils

## Create a Postgres database

> docker run --name postgres-db -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres


## Execute terminal postgres command via line code

> docker exec -it name_container psql -U user -W postgres


