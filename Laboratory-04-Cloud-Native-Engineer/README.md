# Technical Documentation

## Mission Overview

Congratulations! After successfully guiding our clients through multi-cloud evaluations, you have been
promoted to the Cloud-Native Engineering Team at CloudNova Technologies.
Modern cloud computing is no longer just about renting Virtual Machines (VMs) from AWS or Azure. Today's
enterprise applications are built using lightweight, portable, and lightning-fast technologies called Containers.
Your new mission is to understand the shift from traditional virtualization to containerization.
Using the KillerCoda Playground, you will step into the shoes of a Cloud-Native Engineer. You will research the
differences between VMs and containers, execute your very first Docker commands, and deploy a live,
containerized web server in seconds.
Remember: A traditional system administrator manages servers, but a cloud-native engineer manages
the services running on them.


## Objectives

At the end of this laboratory activity, you should be able to: 
- Differentiate between traditional Virtual Machines (VMs) and Containers. 
- Access a Docker-enabled cloud environment using KillerCoda.
- Execute fundamental Docker CLI (Command Line Interface) commands.
- Pull, run, manage, and terminate a containerized application (Nginx).
- Create professional technical documentation of container operations using Markdown.
- Continue developing a well-organized GitHub Cloud Computing Portfolio. 


## Docker Commands Executed

| Command | Description |
|---|---|
| `docker version` | Display Docker version information. |
| `docker info` | Display information about the Docker environment. |
| `docker pull nginx` | Docker retrieves the requested image from the configured registry. |
| `docker run -d -p 8080:80 nginx` | Runs the Nginx container in the background using port 8080. |
| `curl http://localhost:8080` | Tests the Nginx web server. |
| `docker ps` | Lists all containers that are currently running. |
| `docker stop <container_id>` | Stops the running container. |
| `docker ps -a` | Lists both running and stopped containers. |
| `docker rm <container_id>` | Removes the stopped container. |


## Skills Learned

I learned how to use basic Docker commands, pull and run an Nginx container, test a web server. I also learned how to manage the container lifecycle by listing, stopping, checking, and removing containers.

## Challenges Encountered

Some challenges were understanding the difference between an image and a running container, as well as using the correct container ID to stop and remove the container.