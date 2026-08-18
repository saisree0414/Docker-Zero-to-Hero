### 1. Container Management
### docker run
Create and start a new container from an image.
### docker ps / docker container ls
List running containers (-a for all containers).
### docker start <container>
Start one or more stopped containers.
### docker stop <container>
Stop one or more running containers.
### docker restart <container>
Stop and restart a container.
### docker exec -it <container> <cmd>
Execute a command inside a running container.
### docker logs <container>
Fetch logs from a container (-f to stream).
### docker rm <container>
Remove one or more stopped containers (-f to force).
### docker inspect <container>
Return low-level JSON details of a container.
### docker stats
Display a live stream of container resource usage.
### docker cp <container>:<path> <host>
Copy files between container and local host.

# Docker Commands

Some of the most commonly used docker commands are 

### docker images

Lists docker images on the host machine.

### docker build

Builds image from Dockerfile.

### docker run

Runs a Docker container. 

There are many arguments which you can pass to this command for example,

`docker run -d` -> Run container in background and print container ID
`docker run -p` -> Port mapping

use `docker run --help` to look into more arguments.

### docker ps

Lists running containers on the host machine.

### docker stop

Stops running container.

### docker start

Starts a stopped container.

### docker rm

Removes a stopped container.

### docker rmi

Removes an image from the host machine.

### docker pull

Downloads an image from the configured registry.

### docker push

Uploads an image to the configured registry.

### docker exec

Run a command in a running container.

### docker network

Manage Docker networks such as creating and removing networks, and connecting containers to networks.
