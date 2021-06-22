# Azure Compute services

Azure compute provides on-demand pay-as-you-go compunting resources. Some of the most prominent are:

- Azure Virtual Machines
  - IaaS resources to provide VMs
    - Total control of OS, softwares and configurations
    - Virtual machine scale set are an Azure resource that you can use to deploy and manage a set of identical VMs. The scaling process can be manual, automated, or a combination of both.
    - Azure Batch eanbles large-scale parallel and high-performance (HPC) batch jobs with the ability to scale out to a big number of VMs
- Azure Container Instances
  - Containter Instances and AKS are Azure compute resources to deploy and manage containers.
- [Azure App Service](https://docs.microsoft.com/en-us/azure/app-service/)
  - A PaaS offering which allows you to quickly build and scale enterprise-grade web, mobile, and API apps running on any platform.
  - You [pay](https://docs.microsoft.com/en-us/azure/app-service/overview-hosting-plans) for the resources your app uses based on the App Service plan you choose
- [Azure Functions](https://docs.microsoft.com/en-us/azure/azure-functions/) and Logic Apps
  - Serverless architecture
- Azure Virtual Desktop
  - Simplified and performance management for remote desktop and application virtualization service
  - You can BYOL and save on compute costs

<details>
  <summary> Check your knowledge </summary>

1. Which Azure compute resource can be deployed to manage a set of identical virtual machines?

- **Virtual machine scale sets**
- Virtual machine availability sets
- Virtual machine availability zones

*Virtual machine scale sets let you deploy and manage a set of identical virtual machines.*
2. Which of the following services should be used when the primary concern is to perform work in response to an event (often via a REST command) that needs a response in a few seconds?

- **Azure Functions**
- Azure App Service
- Azure Container Instances

*Azure Functions is used when you need to perform work in response to an event (often via a REST request), timer, or message from another Azure service, and when that work can be completed quickly, within seconds or less.*
3. Your company has a team of remote workers that need to use Windows-based software to develop your company's applications, but your team members are using various operating systems like MacOS, Linux, and Windows. Which Azure compute service would help resolve this scenario?

- Azure App Service
- **Windows Virtual Desktop**
- Azure Container Instances

*Azure Virtual Desktop enables your team members to run Windows in the cloud, with access to the required applications for your company's needs.*
</details>
