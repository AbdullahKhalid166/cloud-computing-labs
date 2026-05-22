# ☁️ Lab 01 – AWS EC2 Instance & Web Server Setup

## 📌 Objective
The objective of this lab is to create, manage, and test an AWS EC2 instance and deploy a basic web server using Apache (httpd).

---

## 🛠 Tools & Technologies
- Amazon Web Services (AWS)
- EC2 (Elastic Compute Cloud)
- Linux (Amazon Linux)
- Apache HTTP Server (httpd)
- SSH / EC2 Instance Connect

---

## 📋 Steps Performed

### 🔹 Step 1: Launch EC2 Instance
- Created an EC2 instance using AWS console/commands
- Selected instance type: **t3.micro**
- Connected to instance via EC2 Instance Connect

---

### 🔹 Step 2: Install and Start Apache Server
Executed the following commands:

``bash
sudo yum install httpd -y
sudo systemctl start httpd
sudo systemctl enable httpd
``
