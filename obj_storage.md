
# Object Storage 
- NOTE
! please keep in mind that while the information presented here provides a solid foundation, the cloud landscape is dynamic.
For the most current and accurate details on AWS, Azure, Google Cloud, and Oracle Cloud, we recommend consulting the official documentation and websites of the respective providers.

| Service                 | AWS                                     | Azure                                          | GCP                                         | OCI                     |
| ----------------------- | --------------------------------------- | ----------------------------------------------- | ------------------------------------------- | ----------------------- |
| Object Storage          | Simple Storage Service (S3)              | Azure Blob Storage                              | Google Cloud Storage                        | OCI Object Storage      |
| Object Storage Tiers| S3 Standard, S3 Intelligent-Tiering, S3 Standard-IA, S3 One Zone-IA, S3 Glacier, S3 Glacier Deep Archive | Hot, Cool, Archive, Premium Block Blob | Standard, Nearline, Coldline, Archive | Standard, Archive, Infrequent Access     |
| Visibility              | By default private except the bucket owner. | By default private except storage account owner . | By default private except the bucket owner. | By default private except the owner. |
| Object Size Limit       | Up to 5 TB                               | Up to 190.7 TB                                  | Up to 5 TB                                  | Up to 10 GB (uncompressed) or 10 TB (compressed) |
| Max Storage Size (Per Object) | 5 TB                          | 190.7 TB                                       | 5 TB                                      | 10 GB (uncompressed) or 10 TB (compressed) |
| Object Lifecycle Management | Yes                                | Yes                                             | Yes                                        | Yes                     |
| Lifecycle Rules         | Yes                                   | Yes                                             | Yes                                        | Yes                     |
| Versioning              | Yes, enabled at the bucket level        | yes                                             | yes                                        | Yes, enabled on a bucket, data is not lost when an object is overwritten or when a a delete operation is performed. |
| Replication Rule / policy | replication rules at the bucket level  | replication options at the storage account level | GCP uses object versioning and lifecycle policies | replication options at the bucket level |
| Durability              | Data durability across multi-AZ is 11 9’s. | Data durability across LRS (11 9’s), ZRS (12 9’s), GRS, and RA-GRS, and RA-GRS (16 9’s). | 11 nines over a given year | 11 nines over a given year |
| Object Storage Replication| Cross-Region Replication     | Geo-Replication                      | Object Versioning and Lifecycle Policies | Object Replication and Versioning         |
| CDN                     | Cache content from a static website with Amazon CloudFront. | Cache content from a static website with Azure CDN. | Google Cloud CDN is a globally distributed and highly scalable | Oracle Cloud CDN is a globally distributed content delivery network designed for accelerating web applications and content delivery. |
| Encryption               | Encrypt objects using Client-Side and Server-Side Encryption. | Encrypt storage account using Microsoft- and Customer-manage keys. | | server side encryption with customer provider key or master key stored on VAULT, also client side encryption is supported at the object and metadata level |
| Data Transfer Costs     | Data transfer out of AWS                  | Data transfer in and out of Azure data centers | Data transfer out of GCP                    | Data transfer out of OCI |
| Pricing Model           | Pay-as-you-go                            | Pay-as-you-go                                   | Pay-as-you-go                               | Pay-as-you-go           |
| Object Lock             | Yes                                     | Yes (soft delete)                              | Yes                                         | Yes                     |
| API Support             | S3 REST API                              | Azure Blob REST API                            | GCS JSON API                                | OCI Object Storage API   |
| Data Analytics Integration | AWS Athena                           | Azure Data Lake Storage                        | Google BigQuery                             | Oracle Cloud Data Analytics |
| Security Features       | Encryption at rest and in transit, Access control lists (ACLs), Bucket policies, IAM | Encryption at rest and in transit, Role-based access control (RBAC) | Encryption at rest and in transit, IAM | Encryption at rest and in transit, IAM |
| Endpoints               | Regional endpoints                       | Global and regional endpoints                   | Global endpoints                            | Regional endpoints        |


[multicloud_comparisons](https://github.com/asiandevs/multicloud_comparisons/blob/main/README.md)
