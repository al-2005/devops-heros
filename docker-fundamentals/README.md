# Docker Fundamentals

## Objective
To understand Docker images, containers, and basic container management commands.

## Practical Tasks Completed

### 1. Check Docker Installation
```bash
docker --version
docker ps
```
Verified the installed Docker version and checked running containers.

### 2. Run the Hello World Container
```bash
docker run hello-world
```
Docker downloaded the image and displayed the success message, confirming that Docker was working.

### 3. Inspect Images and Containers
```bash
docker images
docker ps -a
```
Listed available images and all containers, including stopped containers.

### 4. Run an Ubuntu Container
```bash
docker run -it --name ubuntu-practice ubuntu bash
```
Started an interactive Ubuntu container and inspected the operating system:

```bash
cat /etc/os-release
exit
```

The container ran successfully and exited after leaving the shell.

## Commands Practised
- `docker --version` — displays the Docker version.
- `docker ps` — lists running containers.
- `docker images` — lists downloaded images.
- `docker ps -a` — lists all containers.
- `docker run` — creates and runs a container from an image.
- `exit` — exits the interactive container shell.

## Conclusion
I practised running Docker containers, downloading images, inspecting container status, and using an interactive Ubuntu environment.

