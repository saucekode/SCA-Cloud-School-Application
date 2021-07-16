# SCA-DOCKER
Simple application built with springboot and containerized with Docker.

## Getting Started
These instructions will cover usage for the docker container

## Prerequisites
In order to run this container, you'll need docker installed in:

- [Windows](https://docs.docker.com/docker-for-windows/install/)
- [Mac OSX](https://docs.docker.com/docker-for-mac/install/)
- [Linux](https://docs.docker.com/engine/install/)

## How to use docker container

- To download docker image. Run the command:
```
docker pull <docker image name>
```
- To start docker container, use command:
```
docker run <docker image name>
```

## Deployment Instructions

1. Log into Docker using command and enter credentials:
  ```
  docker login
  ```
2. Create tag for docker application using command:
```
docker tag <docker image ID> <dockerhub username>/<docker image name>:<tag name or version>
```
3. Push application to dockerhub using command:
```
docker push <dockerhub username>/<docker image name>:<tag name or version>
```
4. Deployment successful!

### Link to docker repository
[see here](https://hub.docker.com/repository/docker/saucekode/sca-docker)
