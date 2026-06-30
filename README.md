# 🚀 AWS Three-Tier Architecture on AWS

![AWS](https://img.shields.io/badge/AWS-Cloud-orange?style=for-the-badge&logo=amazonaws)
![EC2](https://img.shields.io/badge/EC2-Deployed-success?style=for-the-badge)
![Node.js](https://img.shields.io/badge/Node.js-Backend-green?style=for-the-badge&logo=node.js)
![Apache](https://img.shields.io/badge/Apache-Web_Server-red?style=for-the-badge&logo=apache)
![RDS](https://img.shields.io/badge/Amazon_RDS-MySQL-blue?style=for-the-badge)
![CloudWatch](https://img.shields.io/badge/CloudWatch-Monitoring-purple?style=for-the-badge)

---

## 📌 Project Overview

This project demonstrates a **Production-Style AWS Three-Tier Architecture** deployed on **Amazon Web Services (AWS)**.

The infrastructure is divided into three independent layers:

- 🌐 Web Tier (Apache Web Server)
- ⚙️ Application Tier (Node.js Backend)
- 🗄️ Database Tier (Amazon RDS MySQL)

The application is deployed inside a custom VPC using secure networking principles with monitoring and alerting enabled through CloudWatch and Amazon SNS.

---

# 🏗️ Architecture Diagram

![Architecture](architecture/architecture-diagram.png)

---

# 📐 Architecture Flow

```
Internet
    │
Internet Gateway
    │
Public Subnet
    │
Apache Web Server (EC2)
    │
Private Subnet
    │
Node.js Application (EC2)
    │
Amazon RDS (MySQL)

CloudWatch
     │
Amazon SNS
     │
Email Notification
```

---

# ☁️ AWS Services Used

- Amazon EC2
- Amazon VPC
- Public & Private Subnets
- Internet Gateway
- NAT Gateway
- Route Tables
- Security Groups
- Amazon RDS (MySQL)
- CloudWatch
- Amazon SNS
- IAM
- EC2 Instance Connect Endpoint
- Apache2
- Ubuntu Linux
- PM2

---

# ✨ Features

- Production Style Three-Tier Architecture
- Secure Networking
- Public & Private Subnets
- Apache Web Server
- Node.js Backend
- Amazon RDS Database
- PM2 Process Manager
- CloudWatch Monitoring
- SNS Email Alerts
- Booking API Integration
- Secure Security Groups

---

# 📂 Project Structure

```
aws-three-tier-architecture
│
├── architecture
│   └── architecture-diagram.png
│
├── screenshots
│
├── README.md
```

---

# 🚀 Deployment Workflow

1. Created Custom VPC
2. Configured Public & Private Subnets
3. Created Internet Gateway
4. Configured NAT Gateway
5. Launched EC2 Instances
6. Installed Apache Web Server
7. Deployed Node.js Backend
8. Configured PM2
9. Created Amazon RDS Database
10. Connected Backend with Database
11. Configured CloudWatch Monitoring
12. Configured Amazon SNS Email Alerts
13. Tested Booking API
14. Verified Frontend & Backend Integration

---

# 📸 Deployment Screenshots

## 1. VPC Created
![VPC](screenshots/01-vpc-created.png)

## 2. EC2 Instances Overview
![EC2](screenshots/02-ec2-instances-overview.png)

## 3. Web Server Instance Connection
![Web Server](screenshots/03-web-server-instance-connect.png)

## 4. App Server Instance
![App Server](screenshots/04-app-server-instance-details.png)

## 5. PM2 Installed
![PM2](screenshots/05-pm2-installed.png)

## 6. Backend Running
![Backend](screenshots/06-backend-server-running.png)

## 7. Booking API Success
![API](screenshots/07-booking-api-success.png)

## 8. Amazon RDS
![RDS](screenshots/08-rds-database-created.png)

## 9. NAT Gateway
![NAT](screenshots/09-nat-gateway-created.png)

## 10. EC2 Instance Connect Endpoint
![Endpoint](screenshots/10-vpc-endpoint-created.png)

## 11. CloudWatch Alarm
![Alarm](screenshots/11-cloudwatch-alarm-created.png)

## 12. CloudWatch Email Alert
![Email](screenshots/12-cloudwatch-email-alert.png)

## 13. Frontend Homepage
![Frontend](screenshots/13-frontend-homepage.png)

## 14. Online Booking Form
![Booking](screenshots/14-online-booking-form.png)

## 15. Frontend & Backend Integration
![Integration](screenshots/15-frontend-backend-integration.png)

---

# 📚 Learning Outcomes

- AWS VPC Networking
- EC2 Deployment
- Apache Web Server
- Linux Administration
- Node.js Deployment
- PM2 Process Management
- Amazon RDS Integration
- CloudWatch Monitoring
- Amazon SNS Notifications
- Infrastructure Troubleshooting

---

# 🔮 Future Improvements

- Application Load Balancer
- Auto Scaling Group
- Route 53 Domain
- HTTPS using ACM
- Docker Deployment
- Terraform Automation
- CI/CD Pipeline using GitHub Actions

---

# 👨‍💻 Author

**Krishna Gupta**

Cloud Computing & AWS Enthusiast

⭐ If you like this project, don't forget to Star the repository.
