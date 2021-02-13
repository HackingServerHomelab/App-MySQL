# App-MySQL


## First Time Prerequisites

1. `rm ./Data/mysql/.gitkeep`

## Running the Containers

1. Update the following mount in [docker-compose.yml](./Docker/docker-compose.yml)
    * `../Data/mysql:/var/lib/mysql`
2. Update the following environment variables in [docker-compose.yml](./Docker/docker-compose.yml)
    * `MYSQL_USER=changeme`
    * `MYSQL_ROOT_PASSWORD=changeme`
    * `MYSQL_DATABASE=changeme`
3. Run `docker-compose -f ./Docker/docker-compose.yml up -d`
