# Laboratory 08 – Cloud Security Engineer

## Mission Overview

In the cloud, leaving a server unsecured for even a few minutes can lead to automated brute-force attacks and data breaches. Your mission today applies the security concepts you learned in Chapter 8. You will implement the principle of defense in depth by locking down a live server using a host-based firewall. Using the KillerCoda Playground, you will step into the role of a Cloud Security Engineer. You will deploy a web application, audit the server's open ports, and configure the Uncomplicated Firewall (UFW) to block malicious traffic while allowing legitimate users to access the application. 


## Objectives

- Understand the concept of the Attack Surface and the Principle of Least Privilege (PoLP).
- Perform a basic security audit of active network ports on a Linux server.
- Configure the Uncomplicated Firewall (UFW) with a Default Deny policy.
- Implement granular port management to selectively allow SSH and HTTP traffic.
- Document firewall rules and security best practices using Markdown.
- Continue expanding your professional GitHub Cloud Computing Portfolio. 


## Commands Executed

- `docker run -d --name secure-web-app -p 8080:80 nginx` – Runs an Nginx container in the background and maps port 8080 to port 80.
- `docker ps` – Displays currently running Docker containers.
- `curl http://localhost:8080` – Tests if the Nginx web server is accessible through port 8080.
- `sudo ufw allow ssh` – Allows SSH connections through the firewall.
- `sudo ufw default deny incoming` – Blocks incoming connections by default.
- `sudo ufw default allow outgoing` – Allows outgoing connections by default.
- `sudo ufw enable` – Activates the UFW firewall.
- `sudo ufw status verbose` – Displays the firewall status, rules, and default policies.
- `sudo ufw allow 8080/tcp` – Allows incoming TCP connections through port 8080.
- `sudo ufw status numbered` – Displays firewall rules with numbers for easy identification.


## Skills Learned

- Deploying an Nginx container using Docker.
- Testing web applications with curl.
- Configuring UFW on Ubuntu.
- Applying default firewall policies.
- Managing open network ports.
- Writing technical documentation in Markdown.
- Organizing screenshots and laboratory files in GitHub.
