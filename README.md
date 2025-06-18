# Cloud Engineer Project – Landing Page Deployment

This is a simple landing page project deployed on an AWS EC2 server, styled using Tailwind CSS, and served using Nginx.

---

## 👤 About Me

*Name:* Okudo Chiamaka Favour
*Role:* Cloud Engineer in training  
*Project:* The Future of AI-Powered Logistics  
This project is part of a hands-on cloud engineering exam focused on provisioning servers, configuring web servers, and deploying basic web applications.

---

## ✅ Project Objectives

- Provision a Linux server on the cloud (AWS EC2)
- Set up and secure a web server (Nginx)
- Deploy a basic landing page using HTML + Tailwind CSS
- Make it publicly accessible via HTTP (port 80)
- Document the entire process with a screenshot and GitHub repo

---

## 🧩 Steps I Took

### 1. 🔑 Set Up EC2 on AWS
- Created an EC2 instance with Ubuntu 20.04
- Used altschool-keypair.pem as my SSH key
- Configured security group to allow:
  - *Port 22* – SSH access
  - *Port 80* – HTTP for web access

### 2. 🔌 SSH Into the Server
```bash
ssh -i "altschool-keypair.pem" ubuntu@54.75.131.134
