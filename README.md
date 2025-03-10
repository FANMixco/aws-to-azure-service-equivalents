# AWS to Azure Service Equivalents

## What is this repository about?

This repository provides a detailed, side-by-side comparison of the most popular Amazon Web Services (AWS) and Microsoft Azure services and entities. It helps developers, architects, and cloud engineers understand the similarities between the two cloud platforms, making it easier to plan migrations, hybrid architectures, and multi-cloud deployments. The list includes core services from compute, storage, networking, databases, security, analytics, machine learning, and more, alongside their Azure equivalents. Each service comes with a brief description of its purpose and functionality, helping teams quickly identify the tools they need on either platform.

This resource is invaluable for cloud professionals working across AWS and Azure, simplifying the process of cloud-native development, cost optimization, and seamless integration of workloads in multi-cloud environments.

| **Category**           | **AWS Service/Entity**                  | **Azure Equivalent**                      | **Description**                                                                                 |
|-------------------------|-----------------------------------------|-------------------------------------------|-------------------------------------------------------------------------------------------------|
| **Compute**             | Amazon EC2                             | Azure Virtual Machines                    | Virtual servers for general compute.                                                           |
| **Compute**             | AWS Lambda                             | Azure Functions                           | Serverless computing to run code without provisioning servers.                                 |
| **Compute**             | AWS Elastic Beanstalk                  | Azure App Service                         | Platform-as-a-Service (PaaS) for web applications and APIs.                                    |
| **Compute**             | AWS Auto Scaling                       | Azure Virtual Machine Scale Sets          | Automatic scaling of virtual machines.                                                         |
| **Compute**             | AWS Batch                              | Azure Batch                               | Managed batch processing at scale.                                                             |
| **Compute**             | Spot Instance                          | Spot VM                                   | Access to unused compute capacity at lower cost.                                               |
| **Compute**             | Elastic IP                             | Static Public IP Address                  | Allocates fixed IP addresses for dynamic workloads.                                            |
| **Compute**             | Instance Metadata Service              | Azure Instance Metadata Service           | Provides metadata about VM instances.                                                          |
| **Storage**             | Amazon S3                              | Azure Blob Storage                        | Object storage for scalable data management.                                                   |
| **Storage**             | Amazon EBS                             | Azure Managed Disks                       | Persistent block storage for virtual machines.                                                 |
| **Storage**             | Amazon Glacier                         | Azure Archive Storage                     | Cold storage for infrequently accessed data.                                                   |
| **Storage**             | AWS Storage Gateway                    | Azure StorSimple                          | Hybrid cloud storage solutions.                                                                |
| **Storage**             | Amazon EFS                             | Azure Files                               | Managed file storage with SMB and NFS protocols.                                               |
| **Storage**             | Amazon FSx                             | Azure Files                               | Managed file storage with SMB and NFS protocols.                                               |
| **Storage**             | Snowball Edge                          | Azure Data Box                            | Physical devices for large-scale data transfer.                                                |
| **Databases**           | Amazon RDS for MySQL                             | Azure Database for MySQL                        | Managed relational database services for MySQL.                                                          |
| **Databases**           | Amazon RDS for PostgreSQL                             | Azure Database for PostgreSQL                        | Managed relational database services for PostgreSQL.                                                          |
| **Databases**           | Amazon RDS for MariaDB                             | Azure Database for MariaDB                        | Managed relational database services for MariaDB.                                                          |
| **Databases**           | Amazon RDS for Oracle                             | Oracle Database Service for Azure                        | Managed relational database services for Oracle                                                         |
| **Databases**           | Amazon RDS for SQL Server                             | Azure SQL Database                        | Managed relational database services for SQL Server.                                                          |
| **Databases**           | Amazon Aurora                          | Azure Database for PostgreSQL/MySQL       | High-performance relational databases.                                                         |
| **Databases**           | Amazon DynamoDB                        | Azure Cosmos DB                           | Fully managed NoSQL database service.                                                          |
| **Databases**           | Amazon Redshift                        | Azure Synapse Analytics                   | Data warehousing and analytics.                                                                |
| **Databases**           | Amazon ElastiCache                     | Azure Cache for Redis                     | Managed in-memory caching services.                                                            |
| **Networking**          | Amazon VPC                             | Azure Virtual Network (VNet)              | Private virtual networks for secure resource communication.                                    |
| **Networking**          | Subnet                                 | Subnet                                    | Subdivisions within a VPC/VNet for organizing resources.                                       |
| **Networking**          | Internet Gateway                       | Internet Gateway                          | Connects cloud networks to the internet.                                                       |
| **Networking**          | NAT Gateway                            | NAT Gateway                               | Enables outbound internet traffic for private subnets.                                         |
| **Networking**          | Elastic Load Balancing                 | Azure Load Balancer                       | Automatic distribution of traffic across resources.                                            |
| **Networking**          | Amazon Route 53                        | Azure DNS                                 | Domain Name System management.                                                                 |
| **Networking**          | AWS Direct Connect                     | Azure ExpressRoute                        | Private connections between on-premises and cloud environments.                                |
| **Networking**          | VPC Peering                            | VNet Peering                              | Direct network connectivity between virtual networks.                                           |
| **Networking**          | PrivateLink                            | Private Link                              | Secure connectivity to services over private networks.                                         |
| **Networking**          | VPN Connection                         | VPN Gateway                               | Encrypted connections between on-premises and cloud networks.                                  |
| **Networking**          | Route Table                            | Route Table                               | Determines how traffic is routed within a network.                                             |
| **Networking**          | Security Groups                        | Network Security Groups (NSGs)            | Controls inbound and outbound traffic to resources.                                            |
| **Networking**          | Target Groups                        | Azure Application Gateway Backend Pools            | Manage and route traffic to specific sets of resources.                                            |
| **Identity & Access**   | IAM Role                               | Managed Identity                          | Provides secure access to resources without hardcoding credentials.                            |
| **Identity & Access**   | IAM Policy                             | Azure Role-Based Access Control           | Policies that define access permissions for Azure resources.                                   |
| **Identity & Access**   | AWS Organizations                      | Azure Management Groups                   | Centralized management of multiple accounts or subscriptions.                                  |
| **Identity & Access**   | SAML Federation                        | Azure AD Federation                       | Single sign-on using external identity providers.                                              |
| **Monitoring & Logging**| Amazon CloudWatch/X-Ray                      | Azure Monitor                             | Cloud monitoring and observability.                                                            |
| **Monitoring & Logging**| AWS CloudTrail                         | Azure Activity Log                        | Tracking and auditing cloud resource activity.                                                 |
| **Monitoring & Logging**| AWS X-Ray                              | Azure Application Insights                | Distributed tracing for applications.                                                          |
| **Machine Learning**    | Amazon SageMaker                       | Azure Machine Learning                    | Managed machine learning service.                                                              |
| **Machine Learning**    | AWS Rekognition                        | Azure Cognitive Services                  | Pre-trained models for computer vision, speech, and text analysis.                             |
| **Machine Learning**    | AWS Bedrock                         | Azure OpenAI Service                  | Access to powerful foundation models for generative AI tasks, such as text generation, image creation, and more.                             |
| **Analytics**           | Amazon EMR                             | Azure HDInsight                           | Managed big data frameworks like Hadoop and Spark.                                             |
| **Analytics**           | AWS Glue                               | Azure Data Factory                        | Managed ETL (Extract, Transform, Load) services.                                               |
| **Analytics**           | AWS Glue Data Catalog                  | Azure Purview                             | Metadata management for data assets.                                                           |
| **Analytics**           | Amazon Athena                          | Azure Synapse Serverless SQL Pools        | Querying data stored in object storage.                                                        |
| **Analytics**           | Amazon Kinesis                         | Azure Event Hubs                          | Real-time data streaming.                                                                      |
| **Analytics**           | Amazon EventBridge                         | Azure Event Grid                          | Serverless event bus services for building event-driven applications and real-time event routing.                                                                      |
| **DevOps & Management** | AWS CodePipeline                       | Azure DevOps Pipelines/GitHub Actions     | Continuous integration and delivery (CI/CD) pipelines.                                         |
| **DevOps & Management** | AWS CloudFormation                     | Azure Resource Manager (ARM)              | Infrastructure-as-Code (IaC) for managing cloud resources.                                      |
| **Security**            | AWS KMS                                | Azure Key Vault                           | Managed encryption key services.                                                               |
| **Security**            | AWS Secrets Manager                    | Azure Key Vault Secrets                   | Secure storage for sensitive data like passwords and keys.                                     |
| **Security**            | AWS Shield                             | Azure DDoS Protection                     | Managed protection against distributed denial-of-service (DDoS) attacks.                       |
| **Security**            | AWS Security Hub                       | Microsoft Defender for Cloud              | Unified security management and threat protection.                                             |
| **Migration**           | AWS Migration Hub                      | Azure Migrate                             | Centralized migration planning and execution tools.                                            |
| **Migration**           | AWS Server Migration Service           | Azure Migrate (Server Migration)          | Migrates on-premises workloads to Azure.                                                       |
| **Migration**           | AWS Snowball                           | Azure Data Box                            | Data transfer appliances for large-scale migrations.                                           |
| **Containers**          | Amazon ECS/EKS                             | Azure Kubernetes Service (AKS)            | Managed container orchestration service.                                                       |
| **Containers**          | AWS Fargate                            | Azure Container Instances (ACI)           | Serverless containers.                                                                         |
| **Containers**          | AWS App Runner                            | Web App for Containers           | Deployment and management of containerized applications.                                                                         |
| **Containers**          | AWS ECR                            | Azure Container Registry           | Deployment and management of containerized applications.                                                                         |
| **IoT**                | AWS IoT Core                           | Azure IoT Hub                             | Managed IoT device communication.                                                              |
| **IoT**                | AWS Greengrass                         | Azure IoT Edge                            | Local IoT processing and analysis.                                                             |
| **Blockchain**         | Amazon Managed Blockchain              | Azure Confidential Ledger                 | Secure, verifiable data logging for blockchain-like solutions.                                 |
| **Media Services**     | AWS Elemental MediaConvert              | Azure Media Services                      | Video encoding and streaming services.                                                         |
| **Developer Tools**    | AWS Cloud9                              | Visual Studio Code (Cloud)                | Cloud-based integrated development environments (IDEs).                                         |
| **Networking**          | AWS Global Accelerator                 | Azure Front Door/Azure Traffic Manager    | Improves application performance using global edge networks.                                   |
| **Management**          | AWS Systems Manager Parameter Store    | Azure Automation Variables                | Centralized storage of configuration parameters.                                               |
| **Monitoring & Logging**| AWS CloudWatch Logs                    | Azure Monitor Logs                        | Centralized log monitoring and analysis.                                                       |
| **Messaging**| Amazon SNS (Simple Notification Service)                    | Azure Service Bus                        | Managed service for sending notifications to endpoints like email and SMS.                                                       |
| **Messaging**| Amazon SQS (Simple Queue Service)                    | Azure Queue Storage                        | Managed message queuing service for decoupling and scaling applications.                                                       |
| **Content Delivery Network (CDN)**| AWS CloudFront                    | Azure CDN                        | Global CDN for fast and secure content delivery.                                                       |
| **DevOps and Source Control**| AWS CodeCommit                    | Azure Repos                        | Managed Git repositories for source control.                                                       |
| **DevOps and Source Control**| AWS CodeBuild                    | Azure Pipelines                        | Managed build service for compiling code and running tests.                                                       |
| **DevOps and Source Control**| AWS CodeDeploy                    | Azure DevOps                        | Automated deployment service for applications.                                                       |
| **DevOps and Source Control**| AWS CodeStar                    | Azure DevOps                        | Unified interface for developing, building, and deploying applications.                                                       |
| **Artifact Management**| AWS CodeArtifact                    | Azure CodeArtifact                        | Managed artifact repository for storing and sharing software packages.                                                       |
| **API Management**| AWS AppSync                    | Azure API Management                        | Managed service for building GraphQL APIs.                                                       |
| **API Management**| Amazon API Gateway                    | Azure API Management                       |  Managed service for creating, publishing, and managing APIs at scale.                                                       |
| **Data Integration and ETL**| AWS Glue Studio                    | Azure Data Factory                        | Visual interface for creating and managing ETL jobs.                                                       |
| **Data Transfer**| AWS DataSync                    | Azure Data Box                        | Service for automating data transfers between on-premises and the cloud.                                                       |
| **Web applications**| AWS Amplify/S3                    | Static Web Apps                       |  Deploys full stack web apps with CI/CD workflows, serverless APIs, and global content distribution.                                                       |
| **Infrastructure as Code**| AWS CloudFormation                    | Azure Resource Manager (ARM)                       |  Declarative templates for provisioning and managing cloud resources. Terraform/OpenTofu are some alternatives.                                                       |
| **AI Assistants**| Amazon Q                    | Azure Copilot                       |  AI-powered assistant for enhancing productivity and integrating with enterprise systems.                                                       |



## Contributing to This Repository

We welcome contributions from the community. If you have any suggestions for new questions or answers, please feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License.
