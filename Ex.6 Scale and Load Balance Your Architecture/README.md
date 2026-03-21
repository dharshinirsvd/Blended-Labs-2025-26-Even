# Lab 6 – Scale and Load Balance Your Architecture

## Title

Scale and Load Balance Your Architecture
Author : SAI KRIPA 
Reg no : 212224040284

## Objective

The objective of this lab is to understand how to design a scalable and highly available architecture on AWS using Auto Scaling and Elastic Load Balancing. This experiment focuses on distributing incoming traffic across multiple EC2 instances, automatically scaling resources based on demand, and validating fault tolerance.

## Prerequisites

* Basic knowledge of Amazon EC2 and VPC
* Completion of previous labs (IAM, EC2, EBS, Database Server)
* AWS Academy Lab access
* Stable internet connection

## Tools Used

* AWS Management Console
* Amazon EC2
* Elastic Load Balancer (ELB / ALB)
* Auto Scaling Groups (ASG)
* Amazon CloudWatch

## Tasks Performed

### Task 1: Review Existing Architecture

Students review the existing EC2-based application architecture created in previous experiments.

### Task 2: Create a Launch Template

Students create a launch template that defines the EC2 instance configuration including AMI, instance type, security group, and user data.

### Task 3: Create an Auto Scaling Group

Students create an Auto Scaling Group using the launch template and configure minimum, maximum, and desired instance capacity.

### Task 4: Configure an Application Load Balancer

Students create an Application Load Balancer and configure target groups for routing traffic to EC2 instances.

### Task 5: Register Auto Scaling Group with Load Balancer

Students attach the Auto Scaling Group to the target group of the load balancer.

### Task 6: Configure Scaling Policies

Students configure scaling policies based on CPU utilization using Amazon CloudWatch alarms.

### Task 7: Test Load Balancing and Scaling

Students test the setup by generating traffic and observing automatic scaling and load distribution.

## Workflow (To be filled by Student)

Describe step-by-step how you performed this experiment in your own words.

## Output Screenshots 

<img width="1920" height="1200" alt="Screenshot (207)" src="https://github.com/user-attachments/assets/09009f57-6014-4aed-a627-26f772a0ee26" />
<img width="1920" height="1200" alt="Screenshot (208)" src="https://github.com/user-attachments/assets/fb50ab76-ea96-4920-baf9-1143d430352a" />
<img width="1920" height="1200" alt="Screenshot (209)" src="https://github.com/user-attachments/assets/b4f699ed-2c5b-4f96-a81e-17c8f035c3c3" />
<img width="1920" height="1200" alt="Screenshot (210)" src="https://github.com/user-attachments/assets/2f549ee7-52d8-4862-9af0-73a0edd44cdf" />
<img width="1920" height="1200" alt="Screenshot (211)" src="https://github.com/user-attachments/assets/8f645c3c-8a86-43f4-ab88-c91d52a8f634" />

## Result

This experiment demonstrated how to build a scalable and fault-tolerant cloud architecture using Auto Scaling Groups and Elastic Load Balancing. The system automatically adjusted resources based on workload and ensured continuous service availability by distributing traffic across multiple instances.
