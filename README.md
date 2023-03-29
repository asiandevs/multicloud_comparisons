
# Multicloud Comparisons

Comparing features and services for different Cloud Service Provider in the AWS Cloud, Azure Cloud, Google Cloud and Oracle Cloud
Please let me know if you want to contribute - Any Suggestions / feedback.

- 📫 to reach me **monowar.mukul@gmail.com**. 

​
**Note:** There are several products and services each cloud provides. Initially I am focusing from the High Level ( Top Level) -- in the long run I will add more Low Level. 

----------------------------
# All Products
<sup>:link:-Product page</sup>
<sup>:page_facing_up:-Documentation</sup>

### Infrastructure 
| Function  |AWS | Azure | GCP | OCI |
| --------  | ------------------- | --------------------- |------------------- | --------------------- |
| Regions <br /> [Cluster of Data centre ]  | 25      | 60+.              | 36  | 41  |
| Availability Zones <br /> [ independent / isolated data centre]     |80 AZ  | 180+ (at least 3 per region)   | 109  Zones   | Availability Domain 
|Hardware Grouping  within Data centres <br /> [Availability within zone] | Some more data      | data                  | 
| Point of Presence (POP)  | 230. Edge location  | 130 <br /> spans multiple lines           | 176 POP | |
| Countries | 245    | 140             | 200 | 22 |
| Public Cloud Region  | [ Regions ](https://aws.amazon.com/about-aws/global-infrastructure/regions_az/)   | [ Regions ](https://azure.microsoft.com/en-us/explore/global-infrastructure/geographies/#overview)         | [ Regions ](https://cloud.google.com/about/locations)|  [ Regions ](https://www.oracle.com/cloud/public-cloud-regions/) |


### Networking 
| Networking   Services                        |                                                                                                         |                                                                      |                                |                                                                                   |
|----------------------------------------------|---------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------|--------------------------------|-----------------------------------------------------------------------------------|
| Service                                      | AWS                                                                                                     | Azure                                                                | Google Cloud                   | Oracle                                                                            |
| `Virtual Private Cloud (VPC)`                  | `Amazon VPC`                                                                                              | `Azure VNet`                                        | Google VPC                     | `Virtual Cloud Network `                                                            |
| Default                                      | `Default VPC in each region`                                                                             | `Default VNet is not existing`                                        |     | `No default VCN `                                                                   |
| Allowed VPC size range                       |   /16 to /28                                                                                            | `Subnets are from /29 to /8`                                          |      |  /16 to /30.                                                                      |
| Reserved  IP address<br>(within each subnet) | `5 IP addresses`                                                                             |                                                                      |                                |  `3 IP addresses `                                                          |
| Subnet Types                                 | Private, Public and VPN-only                                                                            | `Private, Public and Gateway`                                          |                                | `regional, availability domain` <br>[` Access type - Private / Public`               |
| Static IP address                            | `can assign a static IPv4 with Elastic IP address`  | `can assign a static IPv4 and IPv6 address` <br>to your resources. |            |                                                                                   |
| Security                                     | `NACLs and Security Groups`    | `NSGs and ASGs`   |   | `Security Lists and NSG`                                                            |
| Gateways                                     | Internet Gateway, Egress-only, <br>NAT Gateway,   <br>Virtual Private Gateway, and <br>Customer Gateway | Types of gateways: <br>VPN Gateway and <br>ExpressRoute Gateway      |                                |  |
| Route Table                                  | `default the main route table` <br>You can create custom one.                                         | Route tables are not automatically associated                        |                                |` Default Route Table without local route`                                           |
| Network area translation                     | NAT Gateway                                                                                             | Virtual Network NAT, <br>Azure Route Server (preview)                | Cloud NAT                      | `NAT gateway, Service Gateway `                                                     |
| Load balancing                               | Elastic Load Balancing (ELB)                                                                            | Application Gateway, Load Balancer, <br>Traffic Manager, Azure DNS   | Cloud Load Balancing           | OCI Load Balancing Service <br>-includes Load Balancer and Network Load Balancer. |
| Peering                                      | A VPC peering between two VPCs.                                                                         | A VPC peering                                                        |                                |          |
| Site 2 site connectivity                     | virtual private gateways and <br>customer gateways                                                      |                                                                      |                                | dynamic routing gateway and <br>customer premises equipment                       |
| Direct Connection                            | AWS Direct Connect                                                                                      | Azure ExpressRoute                                                   | Google Cloud Interconnect      | FastConnect                                                                       |
| Domain name system (DNS)                     | Amazon Route 53                                                                                         | Azure DNS                                                            | Cloud DNS, Google Cloud DNS    | DNS management and <br>traffic management steering policies                       |
| Build, deploy and <br>manage APIs            | Amazon API Gateway                                                                                      | Azure API Apps, <br>API Management                                   | Apigee API Management Platform |                                                                                   |
### Storage

|                                | AWS                                                                                                      | Azure                                                                                        | GCP                                                  | OCI                                                                                                                                                        |
|--------------------------------|----------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------|------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Block Storage                  | Amazon Elastic Block Store                                                                               | Managed Disks                                                                                | Google Compute Engine Persistent Disks               |                                                                                                                                                            |
| Archive Storage                | Amazon Glacier                                                                                           | Azure Archive Blob Storage                                                                   | Google Cloud Storage Nearline                        |                                                                                                                                                            |
| Shared File System             | Amazon Elastic File System | Avere vFXT for Azure, Azure Files, Azure NetApp Files, Azure FXT Edge Filer | Azure File Storage                                                                           | Google Cloud Files [ZFS/Avere]                       | File Storage                                                                                                                                               |
|                                | Elastic Block Storage (EBS)                                                                              | Azure Disk Storage                                                                           | Google Persistent Disks                              | Block volume                                                                                                                                               |
| Bulk Data Transfer             | AWS Snow Family, AWS Import/Export Service                                                               | Azure Data Box, Azure Import/Export Service                                                  | Storage Transfer Service                             | Data Transfer Appliance                                                                                                                                    |
|                                | AWS Import/Export Service                                                                                | Azure Import/Export Service                                                                  |                                                      |                                                                                                                                                            |
| For autobackup                 | Azure Backup                                                                                             | N/A                                                                                          |                                                      |                                                                                                                                                            |
| Object Storage Service         |                                                                                                          |                                                                                              |                                                      |                                                                                                                                                            |
| Object Storage                 | Simple Storage Service (S3)                                                                              | Azure Blob Storage                                                                           | Google Cloud Storage                                 | Object Storage                                                                                                                                             |
| Components                     | S3 is composed of Buckets and objects.                                                                   | Blob storage resources: Storage Account, Container, and Blob                                 |                                                      |                                                                                                                                                            |
| Bucket / naming                | Name is unique                                                                                           | Name is unique                                                                               |                                                      |                                                                                                                                                            |
| Visibility                     | By default disable.                                                                                      | By default disable.                                                                          |                                                      |                                                                                                                                                            |
| Retrival cost                  |                                                                                                          |                                                                                              |                                                      |                                                                                                                                                            |
| Max File Size                  | The maximum file size for each object is 5 TB.                                                           |  The maximum file size for each blob: Block (190.7 TiB), Append (195 GiB), and page (8 TiB). |                                                      | 0B or as large as 10 TiB                                                                                                                                   |
| Max Storage Size               | Bucket capacity is virtually unlimited.                                                                  | Single blob container size is the same as the maximum storage account capacity.              |                                                      |                                                                                                                                                            |
| Tiers                          | S3 tiers: Standard, Standard-IA, One Zone-IA, Intelligent – Tiering, Glacier, Deep Archive               | Blob tiers: Hot, Cool, and Archive.                                                          | Google Cloud Storage Nearline, Coldline, and Archive |                                                                                                                                                            |
| Lifecycle rule - Auto tiering  |                                                                                                          | Yes, called intelligent-tiering                                                              |                                                      | Yes, called Auto-Tiering                                                                                                                                   |
| versioning                     | yes, enabled at the bucket level                                                                         |                                                                                              |                                                      | Yes, enabled on a bucket, data is not lost when an object is overwritten or when a a delete operation is performed.                                        |
| Replication Rule / policy      |                                                                                                          |                                                                                              |                                                      |                                                                                                                                                            |
| Durability                     | Data durability across multi-AZ is 11 9’s.                                                               | Data durability across LRS (11 9’s), ZRS (12 9’s), GRS, and RA-GRS, and RA-GRS (16 9’s).     |                                                      |                                                                                                                                                            |
| Replication                    | Copy objects across S3 buckets in different AWS Regions using Cross-Region Replication.                  | Copy block blobs between a source and destination account using Object Replication.          |                                                      |                                                                                                                                                            |
| CDN                            | Cache content from a static website with Amazon CloudFront.                                              | Cache content from a static website with Azure CDN.                                          |                                                      |                                                                                                                                                            |
| Encryption                     | Encrypt objects using Client-Side and Server-Side Encryption.                                            | Encrypt storage account using Microsoft- and Customer-manage keys.                           |                                                      | server side encryption with customer provider key or master key stored on VAULT, also client side encryption is supported at the object and metadata level |
| Endpoint                       | Endpoint:                                                                                                | Endpoint:                                                                                    |                                                      |                                                                                                                                                            |
|                                | <bucketname> .s3. <region> .amazonaws.com                                                                | <bucketname> .blob.core.windows.net                                                          |                                                      | OCI storage buckets are deployed inside compartments                                                                                                       |

### Compute

### Database 

### Identity and Security
  
### Mangement/  Monitoring

### DevOps CI/CD

### Data Analytics 

### AI and ML

### API Platform and Ecosystems   

### Internet of Things (IoT) 
 
 
----------------------------
### Additional Resources
----------------------------

### Hybrid and multi-cloud
  
  ##Help
  
| Function  |AWS | Azure | GCP | OCI |
| --------  | ------------------- | --------------------- |------------------- | --------------------- |
| User / Group | Some more data      | data                  | 
| Role     |hdladsadslsdadfjdfsdfsdfsfdssdfdsfddsdsdsds  | more data             | ignored
|Policy | Some more data      | data                  | 
| Account    | Some long data here  | more data  <br /> spans multiple lines           | \| character


