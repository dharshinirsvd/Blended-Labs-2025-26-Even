# Lab 5 – Build a Database Server (AWS)

## Author

* **Name**: DHARSHINI R
* **Register Number**: 212224220023

---

## Objective

The objective of this experiment is to understand how to deploy and configure a database server in AWS. This lab focuses on launching an EC2 instance, installing a database management system (DBMS), configuring basic database settings, creating a sample database, and validating connectivity to the database server.

---

## Prerequisites

* Basic understanding of cloud computing concepts
* AWS account or AWS Academy Lab access
* An existing VPC and EC2 knowledge (from previous labs)
* Basic knowledge of Linux commands and SQL

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Security Groups
* SSH Client (Terminal / PuTTY)
* MySQL / MariaDB / PostgreSQL (any one)

---

## Tasks Performed

### Task 1: Launch EC2 Instance for Database Server

Launch a new EC2 instance using Amazon Linux 2 AMI. Select an appropriate instance type and configure key pair and security group.

---

### Task 2: Configure Security Group for Database Access

Modify the security group to allow:

* SSH (Port 22) for remote access
* Database port (e.g., MySQL – 3306 or PostgreSQL – 5432)

---

### Task 3: Connect to EC2 Instance

Connect to the EC2 instance using SSH from your local machine.

---

### Task 4: Install Database Server

Install a database server software such as MySQL, MariaDB, or PostgreSQL on the EC2 instance using package manager commands.

---

### Task 5: Start and Configure Database Service

Start the database service and configure basic settings such as root password and user privileges.

---

### Task 6: Create a Sample Database

Create a sample database and a table inside it. Insert a few records into the table.

---

### Task 7: Test Database Connectivity

Test the database server by connecting to it locally or remotely and performing basic SQL queries.

---

## Workflow (Student Explanation)

(Write the steps you followed in your own words)

1. Create a DB Security Group allowing MySQL (3306) access from the web server.

2. Create a DB Subnet Group with subnets in two Availability Zones.

3. Launch an RDS MySQL Multi-AZ database with required credentials.

4. Connect the web application to the database using the RDS endpoint.

5. Test the app by performing add, edit, delete operations stored in the database


## Output Screenshots (Attach 3)

### Screenshot 1: EC2 Instance for Database Server

<img width="1920" height="1200" alt="Screenshot (201)" src="https://github.com/user-attachments/assets/309db5c9-73c4-4b4c-b727-c81923d8720d" />
<img width="1920" height="1200" alt="Screenshot (202)" src="https://github.com/user-attachments/assets/62eb30d7-28cb-44cd-8c03-daa35ebebbd5" />

### Screenshot 2: Database Service Running

<img width="1920" height="1200" alt="Screenshot (203)" src="https://github.com/user-attachments/assets/b03acd9a-3531-4ee3-aa29-895c3def03f0" />

### Screenshot 3: Sample Database and Table

<img width="1920" height="1200" alt="Screenshot (204)" src="https://github.com/user-attachments/assets/8049be3d-d6b2-4dc2-8844-7e8bf8428db3" />
<img width="1920" height="1200" alt="Screenshot (205)" src="https://github.com/user-attachments/assets/e72ca885-a805-45e9-9cb8-5aa4d3ffcaf9" />


## Result

This experiment demonstrated how to build a database server in AWS using an EC2 instance. By installing and configuring a DBMS, creating a sample database, and testing connectivity, the fundamentals of hosting and managing a cloud-based database server were underst
