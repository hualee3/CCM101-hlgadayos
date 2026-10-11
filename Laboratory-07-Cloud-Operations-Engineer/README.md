# Checkpoint 6 - Technical Documentation 

## Mission Overview

Deploying a cloud application is only the first step; keeping it running smoothly is the real challenge. When a server crashes or a web page takes ten seconds to load, you cannot simply guess what is wrong. You must rely on Observability and Monitoring to see inside your infrastructure. Using the KillerCoda Playground, you will step into the role of a Cloud Operations Engineer. You will establish a performance baseline for your Linux server, deploy a containerized application, generate artificial web traffic, and hunt down performance metrics and system logs to prove the application is healthy. 

## Objectives

At the end of this laboratory activity, you should be able to:
- Utilize native Linux command-line tools to monitor host CPU, Memory, and Disk capacity.
- Deploy a web container and track its real-time performance using Docker metrics.
- Generate web traffic and extract application access logs for analysis.
- Translate raw performance data into a readable technical report using Markdown.
- Continue expanding a professional GitHub Cloud Computing Portfolio. 


## Monitoring Commands Executed

| Command | What It Does |
|---|---|
| `free -h` | Displays total, used, and available RAM |
| `df -h` | Shows disk space usage per filesystem |
| `top` | View the active running processes and CPU load |
| `docker logs client-website` |	Retrieves application access logs showing all HTTP requests |
| `docker stats` | Displays live CPU, memory, and network usage of running containers |                 |

## Skills Learned

- Running an Nginx container using Docker and mapping its port.
- Testing the website and generating a 404 error.
- Checking application logs.
- Monitoring container CPU and memory.
- Recording system monitoring results in Markdown and pushing them to GitHub.

