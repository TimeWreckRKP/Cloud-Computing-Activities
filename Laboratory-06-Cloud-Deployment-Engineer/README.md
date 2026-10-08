# Mission 6: The Cloud Deployment Engineer

## Mission Overview

In this mission, I deployed a multi-container private cloud storage application using Docker Compose. The application uses Nextcloud as the web/application tier and MariaDB as the database tier. I used a Docker Compose YAML file to define the services and deploy them together.

## Objectives

- Understand two-tier and multi-tier application architecture.
- Create and understand a `docker-compose.yml` file.
- Use Nano to create a YAML configuration file.
- Deploy Nextcloud and MariaDB using Docker Compose.
- Connect the application container to the database container.
- Practice Infrastructure as Code (IaC).
- Access a containerized web application through a browser.
- Document the deployment process using Markdown.

## Commands Executed

```bash
mkdir nextcloud-deployment
cd nextcloud-deployment
nano docker-compose.yml
docker-compose up -d
docker-compose ps
docker-compose down
