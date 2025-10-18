### Name: Aderinto Adedayo
### Slack Name: @aderinto adedayo

## PROJECT DESCRIPTION
This project demonstrates how to deploy a lightweight NGINX web server on an AWS EC2 instance and configure it to serve a custom index.html file. The goal is to provision a publicly accessible server that delivers static content from the /var/www/html directory.

## STEPS TO FOLLOW
### STEP 1: 
- Launch EC2 Instance
- Chose Ubuntu as the AMI
- Selected t2.micro instance type
- Created or selected a key pair for SSH access
- Configured security group to allow:
- Port 80 (HTTP)

### STEP 2:
- Connected Via SSH
- Set key permissions
  `ssh -i <key-pair-name.pem> ubuntu@SERVER_IP`

### STEP 3:
- Installed and started NGINX package
  ```bash
  sudo apt update -y
  sudo apt install nginx -y
  sudo systemctl start nginx
  sudo systemctl enable nginx

### STEP 4: 
- Created a custom index.html file in the /var/www/html folder
- Copied the index.html file content fromt he forked github repo and pasted in the /var/www/html/index.html file.

### STEP 5:
- Accessed my web page through my browser on
  WEBPAGE URL `http://3.85.110.54`

## Server IP: http://3.85.110.54

