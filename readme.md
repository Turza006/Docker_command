# Docker Commands

This document provides a list of common Docker commands and their meanings.

## Basic Commands

- **`docker --version`**  
  Displays the installed version of Docker.

- **`docker pull <image>`**  
  Downloads an image from Docker Hub or a specified repository.

- **`docker build -t <image-name>:<tag> <path>`**  
  Builds an image from a Dockerfile located at the specified path.

- **`docker images`**  
  Lists all local Docker images.

- **`docker rmi <image>`**  
  Removes a specified image from the local storage.

- **`docker run <options> <image>`**  
  Runs a container from a specified image.

- **`docker ps`**  
  Lists all running containers.

- **`docker ps -a`**  
  Lists all containers, including stopped ones.

- **`docker stop <container>`**  
  Stops a running container.

- **`docker rm <container>`**  
  Removes a stopped container.

## Container Management

- **`docker exec -it <container> <command>`**  
  Executes a command in a running container (interactive mode).

- **`docker logs <container>`**  
  Displays the logs of a specified container.

- **`docker network ls`**  
  Lists all Docker networks.

- **`docker volume ls`**  
  Lists all Docker volumes.

## Advanced Commands

- **`docker-compose up`**  
  Starts and runs services defined in a `docker-compose.yml` file.

- **`docker-compose down`**  
  Stops and removes services defined in a `docker-compose.yml` file.

- **`docker inspect <container/image>`**  
  Displays detailed information about a container or image.

- **`docker tag <source> <target>`**  
  Adds a new tag to an image.

## Cleanup Commands

- **`docker system prune`**  
  Removes unused data, including stopped containers, unused networks, and dangling images.

- **`docker volume prune`**  
  Removes all unused volumes.

## Conclusion

These commands form the basis of Docker usage. For detailed information, refer to the [Docker documentation](https://docs.docker.com/).