# Mission Reflection

Object storage is a better choice for millions of photos because it is made to handle large amounts of unstructured data. Instead of dividing data into fixed blocks like block storage, it saves each file as an object. It can also grow as more data is added, making it useful for applications where users continuously upload photos.

Docker made the MinIO deployment easier because I was able to create and start the storage server using a command instead of setting up everything manually. The MinIO image already contained what was needed to run the service. I only needed to provide the ports, account credentials, and other settings in the Docker command. This made the deployment process faster and easier to manage.

A bucket is a storage container used to hold objects in an object storage system. During this activity, I created a bucket named `client-photos` and uploaded a sample image to it using the MinIO Web Console. This helped me understand how files can be stored and managed in object storage.

Large enterprise companies can protect their data from physical server failures by keeping copies of the data in different storage locations. Data replication allows copies to be stored across multiple servers or data centers. Backups are also important because they provide separate copies that can be restored if the original data is lost or damaged.

My confidence in using the Linux command line is improving because I am becoming more familiar with Docker commands and working through the terminal. In this activity, I used commands to deploy MinIO and check if the container was running. Completing the steps and seeing the MinIO server work successfully helped me understand how command-line tools are used in cloud computing.