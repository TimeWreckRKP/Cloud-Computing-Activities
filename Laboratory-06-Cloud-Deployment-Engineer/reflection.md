# Mission Reflection

This mission helped me understand why Docker Compose is useful when working with applications that need more than one container. Instead of manually typing many Docker commands, I only needed to create one `docker-compose.yml` file that described the Nextcloud and MariaDB services. After that, I was able to deploy both containers using `docker-compose up -d`. This made the deployment more organized and easier to manage.

I also learned that YAML indentation is very important. When writing the Compose file, the spaces show the relationship between different parts of the configuration. If I use the wrong indentation or use a Tab instead of spaces, Docker Compose may not understand the file correctly and the deployment can fail. This made me realize that even small formatting mistakes can cause problems in Infrastructure as Code.

We used environment variables such as `MYSQL_PASSWORD`, `MYSQL_DATABASE`, and `MYSQL_USER` because they allow the containers to receive the required configuration. I also learned how `MYSQL_HOST=database` allows the Nextcloud container to find the MariaDB container through the Docker Compose network.

Deploying Nextcloud was one of the most interesting parts of the mission because I was able to access a real cloud storage application through my browser after only a few commands. Seeing the Nextcloud setup page made the activity feel more like an actual cloud deployment.

Since Mission 1, my understanding of Cloud Computing has improved. I now understand that cloud computing is not only about using online services. It also involves containers, networking, storage, deployment, automation, and infrastructure management. This mission helped me see how these concepts can work together to build and deploy an application.
