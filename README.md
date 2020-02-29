# FanouseKonkour

## Prerequisites

- Git
- Docker
- php
- phpmyadmin
- mysql
- wordpress

## Configuration

### Docker

1. Remove the .sample extention from docker/docker-compose.yml.sample. Now the file name should be like this :  docker/docker-compose.yml.sample
2. Remove the .sample extention from docker/Dockerfile.sample. Now the file name should be like this :  docker/Dockerfile

## Installing

### Linux Operating System

1. Check the files in the bin/ be executable.
2. Check the docker service is running in your system.
3. Make sure you are in docker directory.
4. Run

```bash
docker-compose up -d
```

in your linux command line. By running this command docker will download the required images then make the containers.
5. Make sure that Docker made the containers. Run

```bash
docker ps -a
```

to see all containers.
6. Enter [https://localhost:8000](https://localhost:8000) to go to wordpress admin page.
7. Enter [https://localhost:8080](https://localhost:8080) to go to phpmyadmin admin page.
