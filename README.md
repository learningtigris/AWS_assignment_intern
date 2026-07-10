# AWS DevOps Assignment

## Objective

Deploy a simple website on AWS EC2 using Nginx.

## AWS Services Used

- Amazon EC2
- Security Group

## EC2 Setup Steps

1. Launched Ubuntu EC2 instance.
2. Created Security Group.
3. Allowed ports:
   - SSH (22)
   - HTTP (80)
4. Connected using SSH.

## Nginx Installation

```bash
sudo apt update
sudo apt install nginx -y
sudo systemctl start nginx
sudo systemctl status nginx
```

## Linux Commands Used

```bash
df -h
free -h
ps -ef
```

## Website

Created a simple HTML page and replaced the default Nginx page.

## Author

Arkobrata Chatterjee
