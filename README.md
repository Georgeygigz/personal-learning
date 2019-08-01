# DOCKER
## Get Started, Part 1: Orientation and setup
### Docker concepts
- Is a platform for developers to develop, deploy and run applications with containers
- `containerization` is the use of linux to deploy applications
- Containerization is increasingly popular because containers are:
- `Flexible`,`Lightweight`, `scalable`, `portable`,`Interchangeable`, `Stackable`

### Images and containers
- Container is launched by an image
- An image is a is an executable package that can launch an application, eg
    the code, a runtime, libraries, environment variables, 
- Container is a runtime instance of an image
- `docker ps` command is used to list the running containers

### Containers and virtual machines
- `Container` shares the kernel of the host machine with other containers
- `VM` runs a full-blown “guest” operating system with virtual access to host resource 

### Prepare your Docker environment
#### List Docker CLI commands
- docker
- docker container --help

#### Display Docker version and info
- docker --version
- docker version
- docker info

#### Execute Docker image
- docker run hello-world

#### List Docker images
- docker image ls

## Get Started, Part 2: Containers
### Introduction
- building an app the Docker way. 

### Your new development environment
- `Docker file` is a portable image containing, application its dependencies,  and the runtime
### Define a container with Dockerfile
- `Docker file` Defines what goes in the environment inside the container
- `docker run -p 8080:80 firstdockerapp`

### Ensure the image works as a deployed container
- `docker run -p 8080:80 username/repo:tag`

## Swarm
### Introduction
- deploying application onto a cluster, running it on multiple machines.
- Swam is a group of machine that are running docker and are joined into cluster

### Set up your swarm
- swarm made of multiple nodes which can be physical or virtual

### Join swarm as worker
- docker swarm init --advertise-addr 192.168.99.101:2376
- docker-machine ssh myvm2 "docker swarm join --token SWMTKN-1-3oh3ik4movgcriqngxrqq5tqssm6gmi8goei82bz778u65l2xb-2fw1m7azbhcnac8m6c7g179ps 192.168.99.101:2376"

### More on docker
- `Docker` is a file where developer defines the application, all the dependencies and requirements 
- `Docker file` is used to create `docker images`
-  When you run docker image we get docker  container
- `Docker` container are the runtime instance of a docker image
-  Image can be stored in docker hub

### Docker
