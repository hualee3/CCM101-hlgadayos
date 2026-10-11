# Mission Reflection

It is important to check the host server's resources even when the containers are running properly because containers still use the host's CPU, memory, and disk space. If these resources become full, the containers may slow down or stop working. Regular monitoring helps identify problems early and makes sure the server has enough resources to support the containers.

If a user cannot log into a web application, I can use `docker logs` to check the container's activity. The logs can show requests, errors, or other problems that may explain why the login is not working. This helps me find the possible cause instead of guessing. I can also use the information from the logs to know what part of the application needs to be checked or fixed.

Logs and metrics provide different information. Logs show specific events that happen in the application, such as successful requests and errors. Metrics show numerical information about performance, such as CPU and memory usage. In this laboratory, `docker logs` showed the HTTP requests, while `docker stats` showed the container's resource usage.

Large companies can use monitoring tools such as Prometheus and Grafana to monitor thousands of containers. Prometheus can collect system metrics, while Grafana can display the information in dashboards. This allows engineers to monitor many containers and quickly find problems.

My Linux troubleshooting skills have improved because I learned how to check system resources, Docker containers, logs, and metrics. I can now use commands such as `free`, `df`, `top`, `docker logs`, and `docker stats` to investigate problems. I also learned that monitoring is important for keeping applications reliable and running properly.