# Laboratory 04 - Cloud-Native Engineer

## Mission Overview

In this laboratory, I learned about Virtual Machines and containers and how they are different from each other. I used the KillerCoda Playground to practice Docker commands. I also downloaded and ran an Nginx container and tested it using `curl`. After that, I practiced stopping and removing the container.

## Objectives

* Learn the difference between VMs and containers.
* Learn how to use Docker commands.
* Pull and run an Nginx container.
* Learn how port mapping works.
* Practice stopping and removing a container.
* Document my Docker activities using Markdown.
* Add my work to my GitHub Cloud Computing Portfolio.

## Docker Commands Executed

### Check Docker Version

```bash
docker --version
```

I used this to check if Docker was installed.

### Check Docker Status

```bash
docker info
```

I used this to check the information and status of the Docker environment.

### Download Nginx

```bash
docker pull nginx
```

I used this to download the Nginx image.

### Run Nginx

```bash
docker run -d -p 8080:80 --name nginx-server nginx
```

I used this to run the Nginx container. The port `8080` on the host was connected to port `80` inside the container.

### Check Running Containers

```bash
docker ps
```

I used this to check if my Nginx container was running.

### Test Nginx

```bash
curl http://localhost:8080
```

I used this to check if the Nginx web server was working. It showed the Nginx welcome page in the terminal.

### Stop the Container

```bash
docker stop nginx-server
```

I used this to stop the Nginx container.

### Check All Containers

```bash
docker ps -a
```

I used this to check the running and stopped containers.

### Remove the Container

```bash
docker rm nginx-server
```

I used this to remove the Nginx container after stopping it.

## Skills Learned

I learned the basic commands used in Docker and how containers work. I learned how to download an image, run a container, use port mapping, and test a web server. I also learned how to stop and remove a container using the terminal. This activity also helped me practice using Markdown and organizing my GitHub portfolio.

## Challenges Encountered

My main challenge was understanding the Docker commands because I was still getting familiar with them. I also had to understand how `8080:80` works when connecting to the Nginx web server. After trying the commands and seeing the results in the terminal, I understood the process better. I also learned that I need to follow the commands carefully when working with Docker containers.

