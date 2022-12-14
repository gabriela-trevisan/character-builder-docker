# Docker-compose to run Character Builder Microservices

## Project setup

#### Create file .env
```
touch .env
```

#### Set the environment variables in .env file

```
MYSQLDB_USER=example
MYSQLDB_ROOT_PASSWORD=example
MYSQLDB_DATABASE=example
MYSQLDB_LOCAL_PORT=3307
MYSQLDB_DOCKER_PORT=3306
NODE_LOCAL_PORT=6868
NODE_DOCKER_PORT=8080
```

#### Build Docker

```
docker-compose up --build
```

## GitHub

#### Docker
```
https://github.com/gabriela-trevisan/character-builder-docker.git
```

#### Character Builder
```
https://github.com/gabriela-trevisan/character-builder.git
```
