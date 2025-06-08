# About <hr/>


# To spin up docker container to run postgresql db <hr />
```shell
docker run --name elasticsearchdemo -p 5433:5432 -e POSTGRES_DB=elasticsearchdemo -e POSTGRES_PASSWORD=sp -e POSTGRES_USER=postgres -d postgres:15
```
