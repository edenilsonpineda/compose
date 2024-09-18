## Docker Compose File for MongoDb

It also has configured a lightweight MySQL database client called Adminer.

Version used:
- MongoDb Community v6.0+ 

### Before running
Create a `.env` file and create the following environment variables: 

```sh
MONGO_INITDB_ROOT_USERNAME="the username that you want"
MONGO_INITDB_ROOT_PASSWORD="a secure password for root user"
```

### HOW TO RUN?
In detached mode
```console
userfoo@host:~$ docker-compose up -d
```
