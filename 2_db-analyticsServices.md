# Azure database and analytics services

Azure database services are globally distributed and supports many of the industry standard databases and APIs.

## Azure Cosmos DB

Azure Cosmos DB is a globally distributed, multi-model database service. You can elastically and independently scale throughput and storage across any number of Azure regions worldwide. Azure Cosmos DB provides comprehensive service level agreements for throughput, latency, availability, and consistency guarantees.

Azure Cosmos DB supports **schema-less** data, which lets you build highly responsive and "Always On" applications to support constantly changing data. Azure Cosmos DB stores data in atom-record-sequence (ARS) format.

## SQL Offerings

Azure offers different SQL databases to let you choose the best which fits your needs.

### Azure SQL Database

Azure SQL Database is a PaaS relational database based on the latest stable version of the Microsoft SQL Server database engine. SQL Database is a high-performance, reliable, fully managed, and secure database. SQL Database is a fully managed service that has built-in high availability, backups, and other common maintenance operations. Microsoft handles all updates to the SQL and operating system code.

You can **migrate** your existing (on-prem or cloud) SQL Server databases with minimal downtime by using the Azure Database Migration Service. The Microsoft Data Migration Assistant can generate assessment reports that provide recommendations to help guide you through required changes prior to performing a migration. After you assess and resolve any remediation required, you're ready to begin the migration process. The Azure Database Migration Service performs all of the required steps. You just change the connection string in your apps.

### Azure database for MySQL

Azure Database for MySQL is a relational database based on the MySQL Community Edition database engine, versions 5.6, 5.7, and 8.0. With it, you have a 99.99 percent availability service level agreement from Azure, powered by a global network of Microsoft-managed datacenters. This helps keep your app running 24/7. With every Azure Database for MySQL server, you take advantage of built-in security, fault tolerance, and data protection that you would otherwise have to buy or design, build, and manage. With Azure Database for MySQL, you can use point-in-time restore to recover a server to an earlier state, as far back as 35 days. You can **migrate** your existing MySQL databases with minimal downtime by using the Azure Database Migration Service.

### Azure Database for PostgreSQL

Azure Database for PostgreSQL is a relational database based on the community version of the open-source PostgreSQL database engine. Azure Database for PostgreSQL is available in two deployment options: **Single Server** and **Hyperscale (Citus)**.

The Hyperscale (Citus) option horizontally scales queries across multiple machines by using sharding. Its query engine parallelizes incoming SQL queries across these servers for faster responses on large datasets. It serves applications that require greater scale and performance, generally workloads that are approaching, or already exceed, 100 GB of data.

### Azure SQL Managed Instance

Azure SQL Database and Azure SQL Managed Instance offer many of the same features; however, Azure SQL Managed Instance provides several options that might not be available to Azure SQL Database. For a complete comparison between the services, refer to the official [documentation](https://docs.microsoft.com/en-us/azure/azure-sql/database/features-comparison).

## Analytics services

Microsoft Azure supports a broad range of technologies and services to provide big data and analytic solutions.

**Azure Synapse Analytics** (formerly Azure SQL Data Warehouse) is a limitless analytics service that brings together enterprise data warehousing and big data analytics. You can query data on your terms by using either serverless or provisioned resources at scale. You have a unified experience to ingest, prepare, manage, and serve data for immediate BI and machine learning needs.

**Azure HDInsight** is a fully managed, open-source analytics service for enterprises. It's a cloud service that makes it easier, faster, and more cost-effective to process massive amounts of data. You can run popular open-source frameworks and create cluster types such as Apache Spark, Apache Hadoop, Apache Kafka, Apache HBase, Apache Storm, and Machine Learning Services. HDInsight also supports a broad range of scenarios such as extraction, transformation, and loading (ETL), data warehousing, machine learning, and IoT.

**Azure Databricks** helps you unlock insights from all your data and build artificial intelligence solutions.

**Azure Data Lake Analytics** is an on-demand analytics job service that simplifies big data.

<details>
  <summary> Check your knowledge </summary>
1. Your development team is interested in writing Graph-based applications that take advantage of the Gremlin API. Which option would be ideal for that scenario?

- **Azure Cosmos DB**
- Azure SQL Database
- Azure Databricks
- Azure Database for PostgreSQL

*Azure Cosmos DB supports SQL, MongoDB, Cassandra, Tables, and Gremlin APIs.*
2. Tailwind Traders uses the LAMP stack for several of its websites. Which option would be ideal for migration?

- Azure Cosmos DB
- **Azure Database for MySQL**
- Azure Database for PostgreSQL

*Azure Database for MySQL is the logical choice for existing LAMP stack applications.*
3. Tailwind Traders has millions of log entries that it wants to analyze. Which option would be ideal for analysis?

- Azure Cosmos DB
- Azure SQL Database
- Azure Database for PostgreSQL
- **Azure Synapse Analytics**

*Azure Synapse Analytics is the logical choice for analyzing large volumes of data.*
</details>
