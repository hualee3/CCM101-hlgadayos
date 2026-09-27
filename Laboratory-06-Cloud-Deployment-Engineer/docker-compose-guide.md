# Docker Compose Guide

## What does the `services:` block do?

The `services:` block defines the different parts of an application that Docker Compose will manage. Each service can have its own image, environment variables, ports, and other settings. This keeps the configuration of multiple containers organized in one YAML file.

## How does the application container find the database container?

The application container uses the `MYSQL_HOST` environment variable to know where the database is located. The value is set to `database`, which is also the service name written under the `services:` block. This allows the application to communicate with the database through the Docker network without exposing the database directly through a public port.

## What is the difference between `docker run` and `docker-compose up -d`?

`docker run` is used to create and start a container from a Docker image. It is useful when working with an individual container. While, `docker-compose up -d` reads the services and settings written in the `docker-compose.yml` file and starts them together. The `-d` option means the containers continue running in the background. This is useful when an application needs more than one container working together.