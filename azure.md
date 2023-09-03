# Compute 

## Batch 
Azure batch is a cloud computer service offered by Microsoft Azure that permits to run large-scale parallel and high-performance computing (HPC) workloads effectively and simply into the cloud. It is created to operate the distributio and administration of compute-intensive jobs over a pool of virtual machines (VMs). 

About the interaction with Python, Microsoft has an official Python SDK for Azure Batch, which let you to interact with Azure batch services programmatically from a Python code. The technician can utilize this SDK to fabricate, manage, and monitor jobs and Batch pools. 

## Web Apps
Azure App Service is an HTTP set-service for hosting REST APIs, mobile back ends, and web apps.  It can be developed in any language, such as Python, Java, NET, NET Core, PHP, and Node.js. These apps run and scale easy with both Linux and Microsoft-based enviroments.

Azure App service can interact with Python in different ways, based on the specific use and service. One way is by leveraring the Azure SDK for Python (Azure SDK), which gives a comprehensive set of libraries and instruments to manage and interact with different Azure services, suc as Azure App Service. 

# Database Services

## Azure Cosmos DB
Azure Cosmos is a fully managed NoSQL and relational database for recent app development. Azure Cosmos DB grants lone-digit millisecond answer time, immediate and automatic scalability, together with assured velocity at any scale. Acting as a entirely managed service, Azure Cosmos DB gets database administration out of your hands with automatic administration, upgrades and patching. It takes care of capacity management with practical serverless and machanical scaling options that answers to application requierements to equal capacity with demand as well. 

To intercat with Azure Cosmos DB using Python, we require to use the official Azure Cosmos db SDK for Python. The SDK gives a timely way to connect to and operate data in the Azure Cosmos DB databases and collections. 

## Azure Table storage. 
Azure Table storage is a service that reserves non-relational structured data, or structurated NoSQL data, in the cloud, giving a characteristic store design without a pattern. Because Table store has not pattern, it is simple to accommodate your data as the requirements of your application develop. Approach to Table storage data is simple and  practical for a lot of types of applications, and it is usually cheaper than conventional SQL for comparable quantity of data. 

To interact using Python, it is require to to use the azure data tables library which gives a Python for Azure Table storage. To install the SDK, it is neccesary to use pip install azure-data-tables. 

# Storage 

## Azure Backup
Azure Backup is a service that gives easy, cost-effective, and secure methods to backup the data and retrieve it from the Microsoft Azure cloud. This service permit organizations to keep their data, workloads, and applications safe by designing secure and trustworthy backups in the Azure cloud. It is created to aid organizations of all sizes guarantee data security, disaster recovery, and organization continuity. 

Microsoft Azure does not offers a specifc Azure Backup SDK or API for interaction directly with Python; instead, we can manage Azure Backup operations utilizing Python indirectly by utilizing Azure SDKs and libraries that are ready for use for Azure Resources Manager and Azure Management APIs.  

## Azure Files 
Azure Files is a cloud-based file repository service offered by Microsoft Azure. It provides a completly managed, scalable and safe method to storage and share files in the cloud via the industry standard Server Message Block (SMB) protocol, Network File System (NFS) protocol, and Azure Files REST API. It is created to address a extended of use cases, from uncomplicated file shares for single users to complicated business applications. SMB Azure files shares are attainable from Linux, Windows, and MacOS customers, while NFS Azure file shares are attainable from Linux customers. 

To interact with Azure Files utilizing Python, we can utilize the Azure Storage File Share client library, which is a segment of the Azure SDK for Python. This library permit to design, manage, and approach Azure file shares from the Python application. 
