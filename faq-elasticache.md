# ElastiCache  FAQs

[https://aws.amazon.com/elasticache/faqs/](https://aws.amazon.com/elasticache/faqs/)

## ElastiCache 
 - Memcache - 1.4.5, 1.4.14, 1.4.24, 1.4.33 and 1.4.34
 - Redis - 2.8.21, 2.8.22, 2.8.23, 2.8.24 and 3.2.4
 
## ElastiCache Benefits
 - fast, managed, in-memory system
 - improve load and response times
 - reduce the cost associated with scaling web applications

## Pricing
 - You pay only for what you use and there is no minimum fee
 - Pricing is per Node-hour consumed for each Node Type
 - Partial Node-hours consumed are billed as full hours
 - There is **no charge for data transfer between Amazon EC2 and ElastiCache within the same Availability Zone**
 - EC2 Regional Data Transfer charges apply when transferring data between an EC2 instance and an ElastiCache Node in different Availability Zones of the same Region
 
## Important Points
  - All clients to an ElastiCache Cluster must be within the Amazon EC2 network, and authorized via security groups
  - Programs running on servers in your own data center cannot access ElastiCache
  - You cannot move an existing ElastiCache Cluster from outside VPC into a VPC