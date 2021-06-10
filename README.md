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

:::image type="content" source="img/azure-services.png" alt-text="Azure-services":::