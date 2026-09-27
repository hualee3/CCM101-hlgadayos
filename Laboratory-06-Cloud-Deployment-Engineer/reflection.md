# Mission Reflection

Using a docker-compose.yml file makes the work of a cloud engineer easier because all container settings can be placed in one configuration file. Instead of running separate commands for every container, the services can be started together using one command. This makes the deployment more organized, easier to manage, and simpler to repeat.

A small indentation mistake in a YAML file can cause problems because YAML uses spaces to understand how the configuration is arranged. Because of this, I check the format carefully before starting the deployment.

Environment variables are also useful for providing the settings needed by different services. Variables such as MYSQL_PASSWORD, MYSQL_DATABASE, MYSQL_USER, and MYSQL_HOST contain the information needed for the application and database to communicate. 

Getting the application to run successfully with only a few commands was one of the most interesting parts of the deployment. Docker Compose was able to start the application and database services together. The docker-compose ps command also made it easy to check if both containers were running properly. This showed how multiple containers can work together as one system.

Since Mission 1, my understanding of cloud computing has improved through the different hands-on activities. The first lessons focused on basic cloud concepts, Linux commands, compute, storage, and networking. Later missions introduced cloud platforms, containers, Docker, cloud storage, and multi-container deployment. These activities made it easier to understand how the different parts of cloud computing are connected. I also became more familiar using Linux commands, creating configuration files, managing containers, and documenting work through GitHub.
