# Docker Compose Guide

## What does the `services:` block do?

The `services:` block defines the containers that will be created and managed by Docker Compose. In my project, there are two services: `database` and `app`. The `database` service uses MariaDB, while the `app` service uses the Nextcloud image.

```yaml
services:
  database:
    image: mariadb:10.6

  app:
    image: nextcloud
