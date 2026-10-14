# Docker Networking

## Objective
To understand Docker networks, communication between containers, and networking with Docker Compose.

## Practical Work

### 1. Docker Compose Setup

Used the existing `session8-docker-networking-volume/docker-compose.yml` configuration to run three services:

- Frontend: Nginx, exposed on port 8080
- Backend: Nginx, available within the Docker network
- Database: MySQL 8.0 with a named volume

### 2. Commands Executed

```bash
docker-compose config
docker-compose up -d
docker-compose ps
curl http://localhost:8080
docker volume ls
```

### 3. Results

- Docker Compose created a default network for the application.
- All three containers started successfully.
- The frontend returned the Nginx welcome page on port 8080.
- Docker created the named volume `session8-docker-networking-volume_db_data` for MySQL storage.

## What I Learned

Docker Compose allows multiple containers to share a network and communicate using service names. Port mapping makes a container service accessible from the host, while named volumes provide persistent storage.

## Conclusion

I practised Docker Compose networking, multi-container deployment, port mapping, and named-volume configuration.

