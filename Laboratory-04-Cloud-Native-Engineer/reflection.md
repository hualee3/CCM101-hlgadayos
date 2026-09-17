## Mission Reflection

Docker containers can start faster than Virtual Machines. A Virtual Machine needs its own operating system, which takes more time to install and start. A Docker container does not need a separate operating system because it shares the host operating system. Because of this, containers use fewer resources and are faster and easier to run. This makes containers useful when applications need to start quickly.

Port mapping is also important when running a web server inside a container. The command **`-p 8080:80`** connects port **8080** of the host to port **80** inside the container. This allowed me to access and test the Nginx web server using **`localhost:8080`**. Without port mapping, accessing the web server from outside the container would be difficult.

The **`docker rm`** command removes a stopped container. The data saved only inside that container is also removed with it. However, the Docker image is not removed, so the same image can still be used to create and run a new container.

Containerization can help developers and IT teams work better together. Developers can put an application and its needed files inside a container. The IT team can then run the same container in another environment. This can reduce problems caused by different system setups. It can also make testing and deployment faster and easier because both teams can work with the same container.

My GitHub portfolio is becoming more organized as I complete each laboratory activity. I am adding Markdown files, Docker commands, explanations, and screenshots that show my work. It now shows more of the skills I am learning in cloud computing, Linux, and Docker. My portfolio also helps me keep a record of my laboratory activities and see how my skills and knowledge improve throughout the course.