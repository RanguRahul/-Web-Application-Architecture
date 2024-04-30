# WEB APPLICATION ARCHITECTURE ON AWS  
Overview

To build the web tier architecture for wordpress website in AWS console


![image](https://github.com/RanguRahul/-Web-Application-Architecture/assets/120587828/2408068a-52c3-4929-9849-57c4aca7ec76)


Description

To build a web application architecture for a WordPress website on AWS, how a classic Multi- Tier web application can be hosted on AWS with various services interconnected. It outlines the process from the web client reaching into the AWS cloud, going through security and management layers before reaching server instances and databases. Different AWS services like Route 53, CloudFront, ACM, NAT gateway, EC2 Instances, EFS, ElastiCache, and RDS are represented with icons and labels. The architecture is divided into different zones including availability zones marked as “Availability Zone 1” & “Availability Zone 2”, public subnets, web subnets etc., each containing specific AWS resources/services.


Prerequisites


Basic knowledge on -

VPC -  Isolated virtual network environment within AWS, allowing customization of network settings and security configurations.

Subnet - Segments of a VPC, dividing the network into smaller, manageable parts. Subnets can be public (accessible from the internet) or private (isolated from the internet).

Amazon EC2 (Elastic Compute Cloud) - Web service which provides resizable compute capacity in the cloud.

Instance - Virtual computing environments

AWS RDS (Relational Database Service) - Managed relational database service, providing easy setup, scaling, and maintenance of SQL databases like MySQL, PostgreSQL, etc.

Elastic Load Balancing - manages the workload on the instances and distributes them to other instances in case of an instance failure

 Application Load Balancers - Ideal for routing HTTP/HTTPS traffic and performing advanced traffic routing and content-based routing.

Amazon Route53 - a highly available and scalable Domain Name System (DNS) web service. You can use Route 53 to perform three main functions in any combination: domain registration, DNS routing, and health checking.

AWS WAF (Web Application Firewall) - a web application firewall that helps you monitor HTTP and HTTPS requests that are forwarded to your protected web application resources.

Amazon CloudFront -  speeds up distribution of your web content by delivering it through a worldwide network of data centers, which lowers latency and improves performance. 

AWS Certificate Manager - helps you create, store, and renew public and private SSL/TLS X.509 certificates and keys that protect your AWS websites and applications.

Amazon S3 (Simple Storage Service) - a highly scalable object storage service. Amazon S3 can be used for a wide range of storage solutions, including websites, mobile applications, backups, and data lakes.

Amazon ElastiCache - helps you set up, manage, and scale distributed in-memory cache environments in the AWS Cloud.

Amazon EFS (Elastic File System) - helps you create and configure shared file systems in the AWS Cloud.

The below link, I elaborate indetail.

https://medium.com/@rahulgoudpk/web-application-architecture-on-aws-66efd62c4996

