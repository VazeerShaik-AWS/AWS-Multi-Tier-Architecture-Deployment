==================================================
PROJECT 1

"BUILD A MULTI-TIER ARCHITECTURE ON AWS"


OBJECTIVE:

Design a highly available and scalable multi-tier application on AWS

Separate web, application, and database layers

Eliminate single points of failure using Multi-AZ design

Follow AWS Well-Architected best practices


PROBLEM STATEMENT:

Monolithic applications are hard to scale and lack fault tolerance

Direct internet access to databases increases security risk


ARCHITECTURE OVERVIEW:

Users access application through Application Load Balancer

Web/App tier runs on EC2 instances in private subnets

Auto Scaling Group handles traffic fluctuations

Database hosted on Amazon RDS (Multi-AZ)

Secure networking using VPC and Security Groups


AWS SERVICES USED:

Amazon VPC

Public and Private Subnets

Internet Gateway

Application Load Balancer (ALB)

Amazon EC2

Auto Scaling Group

Amazon RDS (Multi-AZ)

Security Groups


BUSINESS IMPACT:

High availability and fault tolerance

Secure separation of application layers

Production-ready architecture






## 👨‍💻 Author

**Vazeer Shaik**

Designed and developed as part of my professional cloud portfolio.

Reuse or redistribution without permission is discouraged.
