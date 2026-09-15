# Mission 4 Reflection

This laboratory activity helped me understand the difference between Virtual Machines and containers. I learned that a Docker container can start much faster than a Virtual Machine because it does not need to install and boot a complete operating system. In the activity, I only needed to pull the Nginx image and run a Docker command to create the web server. This made me realize why containers are useful when applications need to be deployed quickly.

The `-p 8080:80` port mapping is important because the Nginx web server is running inside the container on port 80. Port 8080 is the port I used on the host to access the Nginx server. Because of the port mapping, I was able to use `curl http://localhost:8080` and see the Nginx welcome page. This helped me understand how a service inside a container can be accessed from outside the container.

I also learned what happens when using `docker rm`. When I removed the `nginx-server` container, the container itself was deleted. Any data that was stored only inside the container could also be lost. This is why important data should be stored using persistent storage such as Docker volumes.

Containerization can also help developers and IT operations teams work better together. Developers can package an application and its requirements inside a container, while IT teams can run the same container in different environments. This can make deployment more consistent and easier to manage.

My GitHub Cloud Computing Portfolio is also improving because I am adding more practical activities to it. This laboratory allowed me to add Docker commands, screenshots, documentation, and my reflection. I can now show not only what I learned about cloud computing but also some of the practical skills I have developed.
