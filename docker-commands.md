beginner commands:
| Command                                 | Description                               |
| --------------------------------------- | ----------------------------------------- |
| `docker --version`                      | Check Docker version                      |
| `docker info`                           | Display system-wide information           |
| `docker pull <image>`                   | Download an image from Docker Hub         |
| `docker images`                         | List all local images                     |
| `docker ps`                             | List running containers                   |
| `docker ps -a`                          | List all containers (running and stopped) |
| `docker run <image>`                    | Run a container from an image             |
| `docker run -it <image> /bin/bash`      | Run a container interactively with bash   |
| `docker stop <container>`               | Stop a running container                  |
| `docker start <container>`              | Start a stopped container                 |
| `docker restart <container>`            | Restart a container                       |
| `docker rm <container>`                 | Remove a stopped container                |
| `docker rmi <image>`                    | Remove an image                           |
| `docker logs <container>`               | Show logs of a container                  |
| `docker exec -it <container> /bin/bash` | Access running container’s shell          |


Intermediate Commands
| Command                                   | Description                          |
| ----------------------------------------- | ------------------------------------ |
| `docker build -t <name>:<tag> .`          | Build an image from Dockerfile       |
| `docker tag <image> <repo>:<tag>`         | Tag an image                         |
| `docker push <repo>:<tag>`                | Push an image to Docker Hub          |
| `docker inspect <container>`              | Show detailed info about a container |
| `docker cp <container>:/path /local/path` | Copy files from container to host    |
| `docker network ls`                       | List all Docker networks             |
| `docker network inspect <network>`        | Inspect a specific network           |
| `docker network create <name>`            | Create a custom network              |
| `docker volume ls`                        | List all volumes                     |
| `docker volume create <name>`             | Create a volume                      |
| `docker volume inspect <volume>`          | Inspect a volume                     |
| `docker run -v <volume>:/path <image>`    | Attach a volume to a container       |
| `docker stats`                            | Monitor resource usage of containers |


Advanced Commands

| Command                                     | Description                                                |
| ------------------------------------------- | ---------------------------------------------------------- |
| `docker-compose up`                         | Start multiple containers using docker-compose.yml         |
| `docker-compose down`                       | Stop containers and remove network/volumes                 |
| `docker-compose logs -f`                    | Follow logs of all services                                |
| `docker-compose exec <service> /bin/bash`   | Access a running service shell                             |
| `docker system df`                          | Show disk usage by Docker                                  |
| `docker system prune`                       | Remove unused data (images, containers, volumes, networks) |
| `docker save -o <file>.tar <image>`         | Save an image to a tar file                                |
| `docker load -i <file>.tar`                 | Load an image from a tar file                              |
| `docker swarm init`                         | Initialize Docker Swarm mode                               |
| `docker service ls`                         | List services in a swarm                                   |
| `docker service scale <service>=<replicas>` | Scale a swarm service                                      |
| `docker secrets create <name> <file>`       | Create a secret for swarm services                         |
| `docker logs --tail <n> -f <container>`     | Follow last N lines of logs                                |

