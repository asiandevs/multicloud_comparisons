# Database
- NOTE
! please keep in mind that while the information presented here provides a solid foundation, the cloud landscape is dynamic.
For the most current and accurate details on AWS, Azure, Google Cloud, and Oracle Cloud, we recommend consulting the official documentation and websites of the respective providers.

| Database Category        | AWS                                     | Azure                                   | GCP                                      | OCI                                   |
|--------------------------|-----------------------------------------|-----------------------------------------|------------------------------------------|---------------------------------------|
| **Relational Databases**  | Amazon RDS (Multi-AZ, Read Replicas), Amazon Aurora (Multi-Master), Amazon Redshift | Azure SQL Database (Auto-failover Groups, Geo-Replication), Azure Database for MySQL (Geo-Replication), Azure Database for PostgreSQL (Geo-Replication) | Google Cloud SQL (High Availability), Google Cloud Spanner (Global Distribution), BigQuery | Oracle Database Cloud Service (Data Guard, RAC), Oracle Autonomous Database (Regional, Global) |
| **NoSQL Databases**      | Amazon DynamoDB (Global Tables)       | Azure Cosmos DB (Multi-region Writes) | Google Cloud Firestore (Multi-region), Bigtable (Replication), Datastore (Data Redundancy) | Oracle NoSQL Database (High Availability), Oracle Autonomous NoSQL Database (Regional, Global) |
| **In-memory Databases**  | Amazon ElastiCache (Replication)        | Azure Cache for Redis (Replication)  | Google Cloud Memorystore (Regional)      | Oracle Exadata Cloud Service (RAC), Oracle TimesTen (High Availability) |
| **Data Warehouses**      | Amazon Redshift (Backup and Restore)   | Azure Synapse Analytics (Geo-Redundancy) | BigQuery (Multi-Region Data Replication)   | Oracle Exadata Cloud Service (High Availability) |
| **Time Series Databases** | Amazon Timestream (High Availability) | Azure Time Series Insights (High Availability) | Google Cloud Bigtable (Data Replication) | Oracle NoSQL Database (High Availability) |
| **Graph Databases**      | Amazon Neptune (Replication)            | Azure Cosmos DB (Multi-region Writes) | Google Cloud Bigtable (Data Replication) | Oracle Spatial and Graph (High Availability) |
| **Database Backup/Restore** | Amazon RDS Backup and Restore (Automated Backups, Snapshots) | Azure Backup (Data Redundancy) | Google Cloud Backup (Data Redundancy) | Oracle Database Backup Cloud Service (Data Guard, RMAN) |
| **Database Security**     | AWS Identity and Access Management (IAM), Amazon RDS Encryption | Azure Active Directory, Azure SQL Database Firewall Rules | Google Cloud Identity and Access Management (IAM) | Oracle Cloud Identity and Access Management (IAM) |
| **Global Database Deployment** | Amazon RDS Multi-AZ (Global Tables), Amazon Aurora Global Database | Azure Cosmos DB Global Distribution (Multi-master)  | Google Cloud Spanner Global Instance (Global Distribution) | Oracle Global Data Services (GDS), Oracle Data Guard, Oracle RAC |
| **Database Analytics**    | Amazon Redshift Spectrum (High Availability) | Azure Data Lake Analytics (High Availability) | BigQuery (Data Redundancy) | Oracle Database Cloud Service (Analytics) |
| **Managed Database Services**| Amazon RDS, Amazon Aurora            | Azure SQL Database, Cosmos DB      | Cloud SQL                            | Oracle Database Cloud Service, Oracle Exadata Cloud Service |
| **Serverless Databases**    | Amazon Aurora Serverless             | Azure SQL Database Serverless      | Cloud Spanner                        | Oracle Autonomous Database      |
| **Multi-Model Databases**    | Amazon DocumentDB (with MongoDB compatibility) | Azure Cosmos DB (multiple APIs) | Firestore, Bigtable (multi-model capabilities) | Oracle NoSQL Database Cloud - Multi-Model |
| **Database Migration Tools** | AWS Database Migration Service        | Azure Database Migration Service   | Database Migration Service           | Oracle Cloud Database Migration Service |
| **Data Encryption**         | Amazon RDS Encryption, AWS Key Management Service (KMS) | Azure SQL Database Encryption, Azure Key Vault | Google Cloud SQL Encryption, Cloud Key Management Service (KMS) | Oracle Transparent Data Encryption (TDE), Oracle Key Vault |
| **Database Monitoring and Performance Tuning** | Amazon CloudWatch, Amazon RDS Performance Insights | Azure Monitor, Azure SQL Database Query Performance Insights | Google Cloud Monitoring, Cloud SQL Insights | Oracle Cloud Monitoring, Oracle Database Performance Monitoring |
| **Database Replication**    | Amazon RDS Read Replicas, Aurora Replicas | Azure SQL Database Geo-Replication | Cloud SQL Read Replicas, Cloud Spanner Replicas | Oracle Data Guard               |
| **Database Version Control** | AWS Database Migration Service Schema Conversion Tool (SCT) | Azure Database Migration Service Schema Conversion Tool (SCT) | Google Cloud Database Migration Service Schema Conversion Tool (SCT) | Oracle SQL Developer Data Modeler |

[multicloud_comparisons](https://github.com/asiandevs/multicloud_comparisons/blob/main/README.md)
