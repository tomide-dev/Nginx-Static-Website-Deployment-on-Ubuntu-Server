# Static Website Deployment on AWS EC2 Using Nginx

# Project Overview

# This project demonstrates the deployment of a static HTML website on an Ubuntu-based AWS EC2 instance using Nginx. The implementation includes cloud provisioning, web server installation, GitHub-based version control, and deployment validation.

# The objective was to practice Linux system administration, web server configuration, and deployment troubleshooting.

#Tools Used
Amazon Web Services (EC2)
Ubuntu
Nginx
Git
GitHub

#Deployment Steps

##Provision AWS EC2 Instance
Launched EC2 Instance:

Selected Ubuntu Server AMI

Instance type: t3.micro

Configured Security Group:

SSH (Port 22)

HTTP (Port 80)

Connected to the instance via SSH:

##Install Nginx
Updated packages and installed Nginx

Verified service status

##Created index.html
Store Website Code in GitHub

Initialized Git repository and pushed to GitHub

Updated the package repository and installed Nginx

##Deploy Website to Web Root Directory
Removed default Nginx page and cloned repository

Set correct permissions

##Restart and Enable Nginx

##Access Website via Browser
