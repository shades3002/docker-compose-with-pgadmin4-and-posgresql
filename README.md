# Containers with  Pgadmin and Postgresql

Containers needed to build an instance of PgAdmin4 and Postgresql 13.2

## Getting started 

```bash
docker-compose up -d
```

## Stopping Docker Compose
```bash
docker-compose down
```

#### In your web browser

```bash
http://localhost/login
```

#### Setup database

1. Click Add New Server under Quick Links.
2. Enter Name under General. The value can be anything.
3. Enter Host name/address, Username and Password under Connection.

    * For Host name/address {postgres}, the value is the Docker Compose database service name, in our case is {dboards}.
    * For Username, the value is the environment variable POSTGRES_USER {postgres}.
    * For Password, the value is the environment variable POSTGRES_PASSWORD {postgres}.
