# AWS - Day 5

## Create GP3 Volume


### Steps

Login to the portal as specified in document.
In EC2, Elastic Block Store > Volume.

And click create volume

for name, you have to add it like Name > Name specified in document.
image volume as specified in document.
ssd type as specified in document.

### Resources

AWS Elastic Block Store - High Performance Block Storage for the Cloud

- Block Storage- EBS
    -  Low latency Performance
    -  used in databases, and boot volumes. HARD DRIVE for servers.
- Object Storage- S3
    -  Scalable storage for flat data
    -  Accessible via API over the web
- File Storage- EFS
    -  Shared file system for multiple servers
    -  Ideal for content management


What is Amazon EBS?
- Persisiten Block Storage: Acts like a raw, unformatted hard drive attached to your EC2 instance.
- Data Persistence: Unlike Instance Store, data on EBS survives instance termination(if configured ).
- High Availablilty - Automatically replicated within Availability Zone.
- Scalability - Can scale capacity and performaance without downtime.
