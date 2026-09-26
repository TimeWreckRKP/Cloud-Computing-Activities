# Mission 5 Reflection

This laboratory activity helped me understand why cloud storage is important when handling a large amount of data. I learned that Object Storage is better suited for storing millions of photos because it is designed for unstructured data such as images, videos, and backups. Unlike traditional block storage, object storage can organize data as objects and can scale as the amount of data increases. For a photo-sharing application, this makes it more practical for storing many user-uploaded images.

Using Docker also made the deployment of MinIO easier for me. Instead of manually installing and configuring the storage server, I was able to run it inside a container using one Docker command. I also learned how environment variables can be used to set the administrator username and password when starting the container. This made the setup faster and more organized.

A bucket is a storage container in Object Storage where objects or files are stored. In this activity, I created a bucket called `client-photos` and uploaded a test file to it. This helped me understand how cloud applications can organize and manage uploaded data.

For large enterprise companies, I think data can be protected from physical server failures through backups, replication, redundancy, and multiple storage locations. If one physical server fails, another copy of the data can still be available. This helps reduce the risk of permanent data loss.

My confidence in using the Linux command line is also growing. At first, some commands were unfamiliar to me, but after using Docker commands and checking the running container with `docker ps`, I became more comfortable working in the terminal. I learned that carefully reading command output is important when troubleshooting problems. Overall, this activity gave me more practical experience with Docker, Linux, and cloud storage.

