# 📊 EC2 Monitoring Dashboard with CloudWatch Logs & Alarms

This project sets up real-time monitoring and logging for an EC2 instance using AWS CloudWatch. It includes detailed metrics, custom logs, and a dashboard — all built and deployed by me as part of my AWS learning journey. 💪🌩️

---

## 🚀 What It Does

✅ Launches a secure EC2 instance  
✅ Installs and configures Apache web server  
✅ Installs CloudWatch Agent to collect system metrics & logs  
✅ Creates log groups and log streams in CloudWatch  
✅ Builds a custom dashboard displaying real-time metrics (CPU, network, disk, etc.)  
✅ Sets up alarms to monitor CPU usage and get alerts on spikes  

---

## 🧠 What I Learned

- How IAM roles connect services securely  
- Real use of EC2, Security Groups, and Key Pairs  
- Log monitoring and visualization with CloudWatch  
- Creating dashboards and setting thresholds for alerts  
- Hands-on Linux terminal and file editing  
- Git and GitHub for version control and documentation  

---

## 📦 Tech Stack

- **Amazon EC2** (Amazon Linux 2023)  
- **AWS CloudWatch** (logs, metrics, dashboards, alarms)  
- **IAM** (custom role and policy for CloudWatch access)  
- **Apache HTTP Server**  
- **Git + GitHub** (for tracking and publishing this project)

---

## 🌐 Skills Gained

> 🛠️ EC2 Automation  
> 🔐 IAM Permissions  
> 🧩 CloudWatch Agent Config  
> 📉 Metric Dashboards  
> 📡 Monitoring Real-Time Logs  
> 🚨 CPU Alarm Setup  
> 🧠 Real cloud engineering practice  

---

## 👨‍💻 Built & Deployed by: Me (Chea)  
This project is part of my ongoing journey to become a **Cloud Engineer by August 2026** — for my son, my family, and a better future.

🌱 Stay tuned for the next project: **Serverless Lambda Automation**.

# EC2 Auto-Deployed Web Server with Visit Logging

This project auto-deploys an Apache web server on EC2 using Amazon Linux 2023 and EC2 User Data. It installs Apache, PHP, and creates a page that logs every IP visit to a text file.

## What It Does

- Installs Apache and PHP via user data
- Adds a PHP page that logs visitor IP + timestamp to `/var/log/visitlog.txt`
- Uses security groups to allow HTTP and SSH traffic
- Verified via SSH and browser

## Skills Used

- EC2
- User Data
- Apache
- PHP
- IAM Key/SSH
- Security Groups
- Cloud Debugging

