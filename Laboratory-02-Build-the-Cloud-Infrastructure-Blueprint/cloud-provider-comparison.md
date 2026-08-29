# Cloud Provider Comparison

A comparison of the core infrastructure services offered by the three leading
public cloud providers, based on their official documentation.

| Infrastructure Component | AWS | Microsoft Azure | Google Cloud Platform |
|---|---|---|---|
| **Compute** | Amazon EC2 (VMs), AWS Lambda (serverless), AWS Fargate (containers) | Azure Virtual Machines, Azure Functions (serverless), Azure Container Instances | Compute Engine (VMs), Cloud Functions (serverless), Cloud Run (containers) |
| **Storage** | Amazon S3 (object), Amazon EBS (block) | Azure Blob Storage (object), Azure Disk Storage (block) | Cloud Storage (object), Persistent Disk (block) |
| **Networking** | Amazon VPC, AWS Direct Connect | Azure Virtual Network (VNet), Azure ExpressRoute | Google VPC, Cloud Interconnect |
| **Identity and Access Management (IAM)** | AWS IAM | Microsoft Entra ID (formerly Azure Active Directory) | Google Cloud IAM |

## Guide Questions

**1. Which cloud provider offers the broadest range of services? Explain your answer.**
AWS offers the broadest range of services because it was one of the first major public cloud provider that is launched in 2006. Since it has been available for many years, AWS has developed many services for compute, storage, databases, IoT, media, networking, and other areas.

**2. Which cloud platform would you recommend for an organization that primarily uses Microsoft products?**
I would recommend Microsoft Azure because it works well with Microsoft's existing products and services. Tools like Active Directory/Entra ID, Windows Server, Office 365, and SQL Server can easily connect and work with Azure. This makes it easier for organizations that already use Microsoft products because they can manage their accounts, systems, and services in one platform.

**3. Which platform is widely recognized for Artificial Intelligence (AI), Machine Learning (ML), and Kubernetes services?**
Google Cloud Platform is widely recognized for AI, Machine Learning, and Kubernetes services. Google was the company that first created Kubernetes, and its Google Kubernetes Engine (GKE) is widely used for managing containers. GCP also provides AI and Machine Learning tools such as Vertex AI and TensorFlow.

**4. What similarities did you observe among the three cloud providers?**
I observed that all three cloud providers offer the same main types of services, such as compute, storage, networking, and identity and access management. They also use similar cloud features, including pay-as-you-go pricing, the ability to increase or decrease resources when needed, and data centers in different locations around the world. Their services have different names, but many of them have similar uses and functions.