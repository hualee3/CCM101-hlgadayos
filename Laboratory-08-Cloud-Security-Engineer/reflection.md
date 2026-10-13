# Mission Reflection

A host-based firewall protects a server by controlling incoming and outgoing network traffic directly on the server. Even if the physical network perimeter is breached, the firewall can still block unauthorized connections based on its rules. This provides another layer of security and helps prevent attackers from accessing services that should not be publicly available.

Managing open network ports is critical because every open port can provide an entry point for attackers. Closing unnecessary ports reduces the server's attack surface and limits the services that unauthorized users can try to access. In this mission, I allowed SSH for remote administration and port 8080 for accessing the web application while configuring the firewall to deny incoming connections by default.

In a real enterprise environment, leaving a database port like 3306 for MySQL open to the public internet is dangerous because attackers could attempt to exploit vulnerabilities, guess passwords, or gain unauthorized access to sensitive information. Database ports should only be accessible to trusted servers and authorized users whenever possible.

Completing this mission changed my perspective on how easily a server can be compromised. I learned that running a server or application successfully does not automatically mean it is secure. A single misconfigured port or weak firewall rule can create a security risk. I also learned that security requires careful configuration, regular monitoring, and testing.

With eight completed missions, my GitHub portfolio shows my progress in learning cloud computing and server administration. Each mission gives me practical experience in configuring systems, managing containers, monitoring resources, and improving security. I can use these activities as evidence of my learning and as a foundation for more advanced cloud computing tasks in the future.