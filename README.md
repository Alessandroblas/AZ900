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

![Alt text](img/azure-services.png "azuresvcs")

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
| Web | Azure App Service | Quickly create powerful cloud web-based apps.
| Web | Azure Notification Hubs | Send push notifications to any platform from any back end.
| Web | Azure API Management | Publish APIs to developers, partners, and employees securely and at scale.
| Web | Azure Cognitive Search | Deploy this fully managed search as a service.
| Web | Web Apps feature of Azure App Service | Create and deploy mission-critical web apps at scale.
| Web | Azure SignalR Service | Add real-time web functionalities easily.
| IoT | IoT Central | Fully managed global IoT software as a service (SaaS) solution that makes it easy to | IoT |connect, monitor, and manage IoT assets at scale.
| IoT | zure IoT Hub | Messaging hub that provides secure communications between and monitoring of millions of | IoT |IoT devices.
| IoT | IoT Edge | Fully managed service that allows data analysis models to be pushed directly onto IoT devices, | IoT |which allows them to react quickly to state changes without needing to consult cloud-based AI models.
| Big Data | Azure Synapse Analytics | Run analytics at a massive scale by using a cloud-based enterprise data | Big Data | warehouse that takes advantage of massively parallel processing to run complex queries quickly across | Big Data | petabytes of data.
| Big Data | Azure HDInsight | Process massive amounts of data with managed clusters of Hadoop clusters in the cloud.
| Big Data | Azure Databricks | Integrate this collaborative Apache Spark-based analytics service with other big data | Big Data | services in Azure.
| AI | Azure Machine Learning Service | Cloud-based environment you can use to develop, train, test, deploy, manage, and track machine learning models. It can | auto-generate a model and auto-tune it for you. It will let you start training on your local machine, and then scale out to the cloud.
| AI | Azure ML Studio | Collaborative visual workspace where you can build, test, and deploy machine learning solutions by using prebuilt machine learning algorithms and data-handling modules.
| DevOps | Azure DevOps | Use development collaboration tools such as high-performance pipelines, free private Git repositories, configurable Kanban boards, and extensive automated and cloud-based load testing. Formerly known as Visual Studio Team Services.
| DevOps | Azure DevTest Labs | Quickly create on-demand Windows and Linux environments to test or demo applications directly from deployment pipelines.

#### Check your knowledge

1. True or false: You need to purchase an Azure account before you can use any Azure resources.

False
**True**

_You can use a free Azure account or a Microsoft Learn sandbox to create resources._

2. What is meant by cloud computing?

**Delivery of computing services over the internet.**
Setting up your own datacenter.
Using the internet

_That's correct. Cloud computing is the delivery of computing services over the internet, which is otherwise known as the cloud_

3. What is not a reason to move to the cloud?

Faster innovation
**A limited pool of services**
Speech recognition and other cognitive services

_The cloud offers a nearly limitless pool of raw compute, storage, and networking components to help you deliver innovative and novel user experiences quickly._


# Azure fundamental concepts

There are three different cloud models: public, private, and hybrid cloud.

| Deployment model | Description |  |
| - | - | - |
| Public cloud | Services are offered over the public internet and available to anyone who wants to purchase them. Cloud resources, such as servers and storage, are owned and operated by a third-party cloud service provider, and delivered over the internet. | No capital expenditures to scale up. Applications can be quickly provisioned and deprovisioned. Organizations pay only for what they use. 
| Private cloud | A private cloud consists of computing resources used exclusively by users from one business or organization. A private cloud can be physically located at your organization's on-site (on-premises) datacenter, or it can be hosted by a third-party service provider. | Hardware must be purchased for start-up and maintenance. Organizations have complete control over resources and security. Organizations are responsible for hardware maintenance and updates. 
| Hybrid cloud | A hybrid cloud is a computing environment that combines a public cloud and a private cloud by allowing data and applications to be shared between them. | Provides the most flexibility. Organizations determine where to run their applications. Organizations control security, compliance, or legal requirements.

## Cloud computing advantages
There are several advantages that a cloud environment has over a physical environment:
- High availability
- Scalability
- Elasticity 
- Agility
- Geo-distribution
- Disaster recovery

Cloud computing is a **consumption-based model**.
Cloud service providers operate on a consumption-based model, which means that end users only pay for the resources that they use. Whatever they use is what they pay for.A consumption-based model has many benefits, including:

- No upfront costs.
- No need to purchase and manage costly infrastructure that users might not use to its fullest.
- The ability to pay for additional resources when they are needed.
- The ability to stop paying for resources that are no longer needed.

## Cloud Services

Azure offers different *cloud service models*, for instance: IaaS, PaaS, SaaS.

The following illustration demonstrates the services that might run in each of the cloud service models.

![Alt text](img/iaas-paas-saas.png "cloudmodels")

#### Check your knowledge

1. Which of the following choices isn't a cloud computing category?

**Networking-as-a-Service (NaaS)**
Platform-as-a-Service (PaaS)
Infrastructure-as-a-Service (IaaS)
Software-as-a-Service (SaaS)

_That's correct. NaaS isn't a cloud computing category._

2. Which of the following statements is true?

With Operating Expenses (OpEx), you are responsible for purchasing and maintaining your computing resources.
**With Operating Expenses (OpEx), you are only responsible for the computing resources that you use.**
With Capital Expenses (CapEx), you are only responsible for the computing resources that you use.

_That's correct. With Operating Expenses (OpEx), you are only responsible for the computing resources that you use._

3. Which of the following options isn't a type of cloud computing?

**Distributed cloud**
Hybrid cloud
Private cloud
Public cloud

_That's correct. A distributed cloud isn't a valid type of cloud computing._

4. Which of the following choices isn't a benefit of using cloud services?

Scalability
Disaster recovery
High availability
**Geographic isolation**

_That's correct. You can choose to create resources in a single region; however, one of the primary advantages to cloud computing is geographic distribution._

## Azure architectural concepts

In this section we want to explain the following_

- Azure subscriptions and management groups
- Azure resources, resource groups, and Azure Resource Manager.
- Azure regions, region pairs, and availability zones.

### Azure subscriptions, management groups, and resources

- **Resources**: Resources are instances of services that you create, like virtual machines, storage, or SQL databases.
- **Resource groups**: Resources are combined into resource groups, which act as a logical container into which Azure resources like web apps, databases, and storage accounts are deployed and managed.
- **Subscriptions**: A subscription groups together user accounts and the resources that have been created by those user accounts. For each subscription, there are limits or quotas on the amount of resources that you can create and use. Organizations can use subscriptions to manage costs and the resources that are created by users, teams, or projects.
- **Management groups**: These groups help you manage access, policy, and compliance for multiple subscriptions. All subscriptions in a management group automatically inherit the conditions applied to the management group.

The following image shows the top-down hierarchy of organization:

![Alt text](img/hierarchy.png "hierarchy")

### Azure regions, availability zones and region pairs

Azure is made up of datacenters located around the globe, such datacenters aren't exposed to users directly. Instead, Azure organizes them into **regions**.
Resources are therefore created in regions. Some services or VM features are only available in certain regions, such as specific VM sizes or storage types. There are also some global Azure services that don't require you to select a particular region, such as Azure Active Directory, Azure Traffic Manager, and Azure DNS. Azure has specialized regions that you might want to use when you build out your applications for compliance or legal purposes.

**Availability zones** ensure your services and data to be redundant so you can protect your information in case of failure. Availability zones are physically separate datacenters within an Azure region. Note that not every region has support for availability zones. You can use AZs to run mission-critical services but keep in mind that there could be a cost to duplicating your services and transferring data between zones.

Moreover, each Azure region is always **paired** with another region within the same geography (such as US, Europe, or Asia) at least 300 miles away. This approach allows for the replication of resources (such as VM storage) across a geography that helps reduce the likelihood of interruptions because of events such as natural disasters, civil unrest, power outages, or physical network outages that affect both regions at once. If a region in a pair was affected by a natural disaster, for instance, services would automatically failover to the other region in its region pair.

Additional advantages of **region pairs**:

- If an extensive Azure outage occurs, one region out of every pair is prioritized to make sure at least one is restored as quickly as possible for applications hosted in that region pair.
- Planned Azure updates are rolled out to paired regions one region at a time to minimize downtime and risk of application outage.
- Data continues to reside within the same geography as its pair (except for Brazil South) for tax- and law-enforcement jurisdiction purposes.

### Azure resources and Azure Resource Manager

A **resource** consists in a manageable item that's available through Azure. Virtual machines (VMs), storage accounts, web apps, databases, and virtual networks are examples of resources. **Resource groups** is a logical container for resources deployed on Azure. Resources groups can help in: 
- Logical grouping
- Resource life cycle
- Authorization

**Azure Resource Manager** provides a management layer that enables you to create, update, and delete resources in your account. With Resource Manager, you can:
- Manage your infrastructure through declarative templates rather than scripts. A Resource Manager template is a JSON file that defines what you want to deploy to Azure.
- Deploy, manage, and monitor all the resources for your solution as a group, rather than handling these resources individually.
- Redeploy your solution throughout the development life cycle and have confidence your resources are deployed in a consistent state.
- Define the dependencies between resources so they're deployed in the correct order.
- Apply access control to all services because RBAC is natively integrated into the management platform.
- Apply tags to resources to logically organize all the resources in your subscription.
- Clarify your organization's billing by viewing costs for a group of resources that share the same tag.

A **subscription** provides you with authenticated and authorized access to Azure products and services. It also allows you to provision resources. An account can have one subscription or multiple subscriptions that have different billing models and to which you apply different access-management policies. There are two types of subscription boundaries that you can use:
- billing boundary
- access control boundary

You might want to create additional subscriptions for resource and billing management purposes or subscription limits.





#### Check your knowledge

1. Which of the following can be used to manage governance across multiple Azure subscriptions?

Azure initiatives
**Management groups**
Resource groups

*That's correct. Management groups facilitate the hierarchical ordering of Azure resources into collections, at a level of scope above subscriptions. Distinct governance conditions can be applied to each management group, with Azure Policy and Azure role-based access controls, to manage Azure subscriptions effectively. The resources and subscriptions assigned to a management group automatically inherit the conditions applied to the management group.*

2. Which of the following is a logical unit of Azure services that links to an Azure account?

**Azure subscription**
Management group
Resource group
Public cloud

*That's correct. An Azure subscription is a logical unit of Azure services that links to an Azure account.*

3. Which of the following features doesn't apply to resource groups?

Resources can be in only one resource group.
Role-based access control can be applied to the resource group.
**Resource groups can be nested.**

*That's correct. It does not apply, as resource groups can't be nested.*

4. Which of the following statements is a valid statement about an Azure subscription?

Using Azure doesn't require a subscription.
**An Azure subscription is a logical unit of Azure services.**

*That's correct. A subscription is a set of Azure services bundled together for tracking and billing purposes.*