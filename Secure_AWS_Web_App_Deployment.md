# 🌐 AWS Cloud Web App Deployment & Hardening

## 🧠 Summary
This project demonstrates how to deploy and harden a basic web application on Amazon Web Services (AWS) using an EC2 instance and Apache Web Server. The goal was to build foundational skills in cloud infrastructure and cloud security, including configuration, remote access, and system hardening.

---

## 🛠️ Technologies Used
- AWS EC2 (Amazon Linux 2023)
- Apache HTTP Server
- SSH (via PowerShell)
- Firewall/Security Groups
- Bash & Linux CLI

---

## ✅ Tasks Completed

### 1. **Launch EC2 Instance**
- Deployed Amazon Linux 2023 AMI on EC2.
- Generated and downloaded a `.pem` key pair for secure SSH access.
- Configured security group with the following inbound rules:
  - Port 22 (SSH) — My IP only.
  - Port 80 (HTTP) — Open to all (0.0.0.0/0).

### 2. **SSH Into EC2 Instance**
- Connected to the instance using SSH from PowerShell:
  ```bash
  ssh -i "Homelabratory.pem" ec2-user@54.242.7.200

