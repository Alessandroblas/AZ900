# Azure Storage services

**Azure Blob Storage** is an object storage solution that you can use to store unstructured data, such as text or binary data. Blob Storage is ideal for serving images or documents directly to a browser, storing data for archives or distributed access, streaming video and audio, and disaster recovery scenarios. You can store blobs in *containers*, which helps you organize your blobs depending on your business needs. There are three Azure storage **tiers**: hot, cool, and archive.

**Azure File Storage** offers file shares in the cloud, and shares are accessible using industry standard network protocols (a typical SMB share). Mounting Azure file shares is just like connecting to shares on your local network.

**Azure Disk Storage** provides disks for virtual machines and applications. Azure offers both solid state drives conventional hard drives.

**Azure Table Storage** offers a NoSQL data store for key value pairs using large scale datasets.

**Azure Queue Storage** provides asynchronous message queuing for communication between application components.

<details>
  <summary> Check your knowledge </summary>
1. What is the first step that you would take in order to share an image file as a blob in Azure Storage?

- Create an Azure Storage container to store the image.
- **Create an Azure Storage account.**
- Upload the image file and create a container.
- Use a Shared Access Signature (SAS) token to restrict access to the image.

*You must create an Azure Storage account before you can use any Azure Storage features.*

2. Which Azure Storage option is better for storing data for backup and restore, disaster recovery, and archiving?

- Azure Files Storage
- Azure Disk Storage
- **Azure Blob Storage**

*Azure Blob Storage is your best option for storing disaster recovery files and archives.*
</details>

Offical docs [here](https://docs.microsoft.com/en-us/azure/storage/)
