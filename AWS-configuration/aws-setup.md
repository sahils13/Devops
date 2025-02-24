# AWS Setup Documentation

This document explains the basic AWS setup steps:

## 1. Creating an EC2 Instance
- Login to AWS Console
- Go to EC2 Service
- Click on "Launch Instance"
- Select an AMI, Instance Type, and Configure Network

## 2. Security Group Setup
- Add rules for SSH (22), HTTP (80), and HTTPS (443)
- Restrict access to trusted IPs

## 3. Auto Scaling Setup
- Create an Auto Scaling Group
- Define Min/Max Instances

## 4. Attaching a Volume
- Navigate to EBS
- Create and attach a new volume to the instance

