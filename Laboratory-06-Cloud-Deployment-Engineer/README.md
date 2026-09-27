# Laboratory 06 - Cloud Deployment Engineer

## Mission Overview

Your flawless work in deploying data storage solutions has earned you a spot on the Cloud Deployment Team at CloudNova Technologies. Up until now, you have been deploying single containers (like a standalone web server or a storage bucket). However, real-world enterprise applications are rarely just one container. They are "multi-tier" systems that require a frontend web application communicating seamlessly with a backend database. Deploying these one by one manually is prone to error. Enter Docker Compose. In this mission, you will transition from manual commands to Infrastructure as Code (IaC). Using a YAML configuration file, you will define a multi-container private cloud storage application
(Nextcloud and MariaDB) and deploy the entire stack simultaneously with a single command!

## Objectives

At the end of this laboratory activity, you should be able to:
- Explain the concept of a multi-tier application architecture.
- Understand the purpose and structure of a docker-compose.yml file.
- Use a Linux command-line text editor (nano) to create configuration files.
- Deploy a multi-container application (Nextcloud + Database) using Docker Compose.
- Document deployment procedures and Infrastructure as Code (IaC) principles using Markdown.
- Continue expanding your professional GitHub Cloud Computing Portfolio. 

## Commands Executed

| Command | Description |
|---|---|
| `mkdir nextcloud-deployment` | Creates a new directory for the deployment. |
| `cd nextcloud-deployment` | Moves into the project directory. |
| `nano docker-compose.yml` | Creates and opens the Docker Compose file using nano. |
| `cat docker-compose.yml` | Displays the contents of the Docker Compose file. |
| `docker-compose up -d` | Starts the services and runs them in the background. |
| `docker-compose ps` | Checks the status of the containers. |
| `docker-compose down` | Stops and removes the containers. |

## Skills Learned

- Creating and editing a YAML file.
- Using Docker Compose to manage multiple containers.
- Running container services in the background.
- Checking the status of running containers.
- Understanding how containers communicate through a network.
- Using port mapping to access an application.
- Stopping and removing containers properly.