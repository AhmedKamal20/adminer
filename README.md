# Adminer ( Database Playground)

## To start
`cd adminer`

`docker-compose up -d`

## Then Go to
http://localhost:8080/

## For MySQL
```
System: MySQL
Server: mysql-db
Username: root
Password: root
Database:
```

## For PostgreSQL
```
System: PostgreSQL
Server: postgres-db
Username: postgres
Password: postgres
Database:
```

## To Monitor Docker
`lazydocker`

## Shared Folder
There is a directory in this repo called `shared`, it's mounted into the mysql/postgres container on the root dir, so you can move files in and out of the container easily.
