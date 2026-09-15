
# Docker Deployment

## Nginx Deployment

### Pull the Nginx Image

```bash
docker pull nginx
```

This command downloads the official Nginx image from Docker Hub.

### Run the Nginx Container

```bash
docker run -d -p 8080:80 --name nginx-server nginx
```

This command creates and runs the Nginx container in detached mode and maps host port 8080 to container port 80.

### List Running Containers

```bash
docker ps
```

This command displays the Docker containers that are currently running.

### Test the Nginx Web Server

```bash
curl http://localhost:8080
```

This command sends a request to the Nginx web server and displays the returned HTML content.

## Container Lifecycle

### Stop the Running Container

```bash
docker stop nginx-server
```

This command stops the running Nginx container.

### Verify the Container is Stopped

```bash
docker ps
```

This command checks the running containers and confirms that the stopped Nginx container is no longer listed.

### View All Containers

```bash
docker ps -a
```

This command displays all containers, including containers that have been stopped.

### Remove the Container

```bash
docker rm nginx-server
```

This command removes the stopped Nginx container completely.

## Screenshot Evidence

The screenshot below shows the container lifecycle commands that I executed:

`container-lifecycle.png`
