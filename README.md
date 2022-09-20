# springboot-postgres-demo
This is a simple demo for using SpringBoot with PostgreSQL

## Start a Postgres instance via Docker
```
docker run --name postgres-spring -e POSTGRES_PASSWORD=somepassword -d -p 5432:5432 postgres:alpine
```
