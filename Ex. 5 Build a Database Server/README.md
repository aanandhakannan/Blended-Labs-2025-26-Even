# Lab 5 – Build a Database Server (AWS)

## Author

* **Name**: __AANANDHA KANNAN S______________________________
* **Register Number**: ___212224040003__________________
* **Date of Submission**: ___18-03-2026_______________

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

1. Launch EC2 instance with Amazon Linux 2.

2.Configure security group for SSH and DB port.

3.Connect to instance through SSH.

4.Install MySQL/MariaDB/PostgreSQL.

5.Start DB service and configure security basics.

6.Create sample database, table, and insert records.

7.Test local and remote database connectivity.

## Output Screenshots (Attach 3)

### Screenshot 1: EC2 Instance for Database Server

<img width="676" height="335" alt="image" src="https://github.com/user-attachments/assets/2644b03d-0b11-4248-a5fd-131f8246c7b5" />


---

### Screenshot 2: Database Service Running

<img width="676" height="330" alt="image" src="https://github.com/user-attachments/assets/9158861d-fb9a-4434-a99d-7debfc239170" />


---

### Screenshot 3: Sample Database and Table

<img width="618" height="322" alt="image" src="https://github.com/user-attachments/assets/5f9fa488-4cda-498a-bbfd-4165db398c2b" />

---

## Result

This experiment demonstrated how to build a database server in AWS using an EC2 instance. By installing and configuring a DBMS, creating a sample database, and testing connectivity, the fundamentals of hosting and managing a cloud-based database server were underst
