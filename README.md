# AWS Multi-Tier Architecture

## Overview

Designed a highly available and scalable multi-tier architecture on AWS by separating web, application, and database layers following AWS Well-Architected best practices.

## Objective

* Design a scalable and fault-tolerant application architecture
* Separate web, application, and database tiers
* Eliminate single points of failure using Multi-AZ deployment
* Ensure secure and efficient networking

## Problem Statement

* Monolithic applications are difficult to scale and maintain
* Lack of fault tolerance leads to downtime
* Direct database exposure increases security risks

## Architecture

* Users access the application via an Application Load Balancer (ALB)
* EC2 instances deployed in private subnets handle web and application logic
* Auto Scaling Group dynamically adjusts capacity based on traffic
* Amazon RDS configured in Multi-AZ for high availability
* VPC with public and private subnets ensures secure network isolation

## Architecture Diagram

<p align="center">
  <img src="diagrams/architecture.png" width="700">
</p>

## AWS Services Used

* Amazon VPC
* Public and Private Subnets
* Internet Gateway
* Application Load Balancer (ALB)
* Amazon EC2
* Auto Scaling Group
* Amazon RDS (Multi-AZ)
* Security Groups

## Outcome / Business Impact

* Achieved high availability and fault tolerance
* Improved scalability using Auto Scaling
* Enhanced security through proper network segmentation
* Built a production-ready cloud architecture

## Author

**Vazeer Shaik**
AWS Cloud Engineer

---

This project demonstrates hands-on expertise in designing scalable and secure multi-tier architectures on AWS.
