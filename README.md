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

