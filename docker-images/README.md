# Docker Images

## Objective
To practise pulling, inspecting, and running Docker images.

## Practical Tasks Completed

### 1. Pull an Image
```bash
docker pull nginx
```
Downloaded the Nginx image from Docker Hub.

### 2. Inspect Available Images
```bash
docker images nginx
```
Listed the downloaded Nginx image.

### 3. Run a Container
```bash
docker run -d --name nginx-practice -p 8081:80 nginx
```
Started Nginx in detached mode and mapped host port `8081` to container port `80`.

### 4. Verify the Container
```bash
docker ps
curl http://localhost:8081
```
Confirmed that the container was running and returned the default Nginx welcome page.

## Conclusion
I practised pulling a Docker image, listing images, running a container with port mapping, and verifying the web server response.

