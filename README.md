# What is Azure?

Azure is a set of cloud services that help your organization meet your current and future business challenges. 
It offers everything you need to  build, manage, and deploy applications on a massive global network.

Azure main pillars:
- Continuous innovation 
- You choose
- Hybrid cloud
- Trust

## How does it work?

Azure use virtualization on a massive scale to abstract physical resources to the users. Each Azure data center has many racks filled with servers and each servers includes a hypervisor to run multiple virtual machines and services. All of these servers are connected to a network switch providing connectivity. A special server in the rack contains a special piece of software called a *Fabric Controller*. Each Fabric Controller is then connected to another special component known as the *Orchestrator*, which is responsible for managing everything that happens in Azure including users requests. Users make requests using the *Orchestrator Web API* thorugh different tools, including the Azure portal or CLI.

### What is the Azure Portal?

The [Azure portal](https://portal.azure.com/) is a console that provides an alternative to the command-line tools. 
Through the portal you can: 

- Build, manage and monitor your resources
- Create dashboard for custom views of resources
- Configure accessibility options for an optimal experience

The Azure portal is designed for resiliency, continuous availability and improvement; it mantains a presence in every Azure DC.

### What is the Azure Marketplace?
[Azure Marketplace](https://azuremarketplace.microsoft.com/)  connects users with Microsoft partners, independent software vendors, and startups that are offering their solutions and services, which are optimized to run on Azure. All solutions and services are certified to run on Azure.


# Azure services

Azure has such an extensive array
of services and features. we can divide them into 10 main categories: 


- Compute

These cloud services let you scale your computing capability on demand while only paying for what you use. Add virtual machines as needed or scale your company's app services for web and mobile apps.

- Networking

These features let you connect your cloud and on-premise infrastructure in order to bring the best possible experience to your customers. 

- Storage

Whether it's disk, file, blob, or archival storage, these services let you scale your data and app storage needs in a secure fashion.

- Mobile

With the mobile services, you can build and deploy cross-platform and native apps for any mobile device, send notifications, use Xamarin to build cloud-powered apps, and take advantage of cognitive services to make your app smarter.

- Databases

Choose from a variety of proprietary and open source database engines to bring and manage your databases to the cloud. 

- Web

These services help you build, deploy, manage, and scale your web applications.

- Internet of Things

Use these features to connect, monitor, and manage all of your IoT assets. Analyze the data as it arrives from sensors and then take meaningful action with it.

- Big data

When you have large volumes of data, these open source cluster services will help you run  analytics at a massive scale and make data drive decisions.

- AI

Use your existing data to forecast future behaviors based on these AI services. Use machine learning to build, train, and deploy models to the cloud.

- DevOps

DevOps brings together people, processes, and technology by automating software delivery to provide continuous value to your users.

Here's a big-picture view of the available services and features in Azure.

![Alt text](img/azure-services.png "Optional title")

| Service Type | Service name | Service function |
| ------------ | ------------ | --------------- |
| Compute | Azure Virtual Machines | Windows or Linux virtual machines (VMs) hosted in Azure. 
| Compute | Azure Virtual Machine Scale Sets | Scaling for Windows or Linux VMs hosted in Azure. 
| Compute | Azure Kubernetes Service |  Cluster management for VMs that run containerized services.
| Compute | Azure Service Fabric | Distributed systems platform that runs in Azure or on-premises.
| Compute | Azure Batch | Managed service for parallel and high-performance computing applications.
| Compute | Azure Container Instances | Containerized apps run on Azure without provisioning servers or VMs.
| Compute | Azure Functions | An event-driven, serverless compute service.
|Network| Azure Virtual Network | Connects VMs to incoming virtual private network (VPN) connections.
|Network| Azure Load Balancer | Balances inbound and outbound connections to applications or service endpoints.
|Network| Azure Application Gateway | Optimizes app server farm delivery while increasing application security.
|Network| Azure VPN Gateway | Accesses Azure Virtual Networks through high-performance VPN gateways.
|Network| Azure DNS | Provides ultra-fast DNS responses and ultra-high domain availability.
|Network| Azure Content Delivery Network | Delivers high-bandwidth content to customers globally.
|Network| Azure DDoS Protection | Protects Azure-hosted applications from distributed denial of service (DDOS) |Network| attacks.
|Network| Azure Traffic Manager | Distributes network traffic across Azure regions worldwide.
|Network| Azure ExpressRoute | Connects to Azure over high-bandwidth dedicated secure connections.
|Network| Azure Network Watcher | Monitors and diagnoses network issues by using scenario-based analysis.
|Network| Azure Firewall | Implements high-security, high-availability firewall with unlimited scalability.
|Network| Azure Virtual WAN | Creates a unified wide area network (WAN) that connects local and remote sites.
| Storage| Azure Blob storage | Storage service for very large objects, such as video files or bitmaps.
| Storage| Azure File storage | File shares that can be accessed and managed like a file server.
| Storage| Azure Queue storage | A data store for queuing and reliably delivering messages between applications.
| Storage| Azure Table storage | Table storage is a service that stores non-relational structured data (also known as structured NoSQL data) in the cloud, providing a key/attribute store with a schemaless design.
| Database | Azure Cosmos DB | Globally distributed database that supports NoSQL options.
| Database | Azure SQL Database | Fully managed relational database with auto-scale, integral intelligence, and robust | Database | security.
| Database | Azure Database for MySQL | Fully managed and scalable MySQL relational database with high availability | Database | and security.
| Database | Azure Database for PostgreSQL | Fully managed and scalable PostgreSQL relational database with high | Database | availability and security.
| Database | SQL Server on Azure Virtual Machines | Service that hosts enterprise SQL Server apps in the cloud.
| Database | Azure Synapse Analytics | Fully managed data warehouse with integral security at every level of scale at | Database | no extra cost.
| Database | Azure Database Migration Service | Service that migrates databases to the cloud with no application code | Database | changes.
| Database | Azure Cache for Redis | Fully managed service caches frequently used and static data to reduce data and | Database | application latency.
| Database | Azure Database for MariaDB | Fully managed and scalable MariaDB relational database with high | Database | availability and security.
