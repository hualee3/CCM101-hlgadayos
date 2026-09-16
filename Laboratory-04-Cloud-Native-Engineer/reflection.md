## Mission Reflection

Docker containers can start faster than Virtual Machines. A Virtual Machine needs its own operating system, which takes more time to install and start. A Docker container does not need a separate operating system because it shares the host operating system which makes containers faster and easier to run.

Port mapping is also important when running a web server inside a container. The command **`-p 8080:80`** connects port **8080** of the host to port **80** inside the container. This allowed me to access and test the Nginx web server using **`localhost:8080`**.

The **`docker rm`** command removes the stopped container and the data saved only inside that container can also be removed with it. The Docker image is not removed, so it can still be used to create another container.

Containerization can help developers and IT teams work better together. Developers can put an application and its needed files inside a container. The IT team can then run the same container in another environment. This can reduce problems caused by different system setups and make testing and deployment easier.

My GitHub portfolio is becoming more organized as I complete each laboratory activity. I am adding Markdown files, Docker commands, explanations, and screenshots that show my work. It now shows more of the skills I am learning in cloud computing, Linux, and Docker. It also helps me keep a record of my activities and see my progress.


