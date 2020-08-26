# Ruby Dev Env
This is a dev enviroment for running ruby without concerning about it's installation


## Requirements 

[Docker installation](https://docs.docker.com/get-docker/)
[Docker-compose installation](https://docs.docker.com/compose/install/) (for linux only. Please don't install from apt-get)

## Running container

```bash

docker-compose build
docker-compose run --rm --service-ports ruby_dev

```

