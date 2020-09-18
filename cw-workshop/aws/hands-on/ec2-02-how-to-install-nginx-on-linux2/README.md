# Hands-on EC2-02 : How to Install Nginx Web Server on EC2 Linux 2

Purpose of the this hands-on training is to give the students basic knowledge of how to install Nginx Web Server on Amazon Linux 2 EC2 instance.

## Learning Outcomes

At the end of the this hands-on training, students will be able to;

- demonstrate their knowledge of how to launch AWS EC2 Instance.

- establish a connection with AWS EC2 Instance with SSH.

- install the Nginx Server on Amazon Linux 2 Instance.

- configure the Nginx Server to run simple HTML page.

- write a simple bash script to run the Web Server

- automate the process of installation and configuration of a Web Server using the `user-data` script of EC2 Instance.

## Outline

- Part 1 - Launching an Amazon Linux 2 EC2 instance and Connect with SSH

- Part 2 - Installing and Configuring Nginx Web Server to Run a Simple Web Page

- Part 3 - Automation of Web Server Installation through Bash Script

![nginx HTTP Server](./nginx-troubleshooting-logo.jpg)

## Part 1 - Launching an Amazon Linux 2 EC2 instance and Connect with SSH

- Launch an Amazon EC2 instance with AMI as `Amazon Linux 2`, instance type as `t2.micro` and default VPC security group which allows connections from anywhere and any port.

- Connect to your instance with SSH.

```bash
ssh -i [Your Key pair] ec2-user@[Your EC2 IP / DNS name]
```

## Part 2 - Installing and Configuring Nginx Web Server to Run a Simple Web Page

- Update the installed packages and package cache on your instance.

```bash
sudo yum update -y
```

- Install the Nginx Web Server.

```bash
sudo amazon-linux-extras install nginx1.12
```

- Start the Nginx Web Server.

```bash
sudo chkconfig nginx on
```

- Go to `/usr/share/nginx/html` folder.

```bash
cd /usr/share/nginx/html
```

- Show content of folder.

```bash
ls
```

- Remove existing `index.html`.

```bash
sudo rm index.html
```

- Upload new `index.html` and `ken.jpg` files with `wget` command.

```bash
sudo wget https://raw.githubusercontent.com/awsdevopsteam/route-53/master/index.html
sudo wget https://raw.githubusercontent.com/awsdevopsteam/route-53/master/ken.jpg
```

- start the Nginx Web Server.

```bash
sudo service nginx start
```

- Check if the Web Server is working properly from the browser.

## Part 3 - Automation of Web Server Installation through Bash Script (User data)

- Configure an Amazon EC2 instance with AMI as `Amazon Linux 2`, instance type as `t2.micro`, default VPC security group which allows connections from anywhere and any port.

- Configure instance to automate web server installation with `user data` script.

```bash
#! /bin/bash
yum update -y
amazon-linux-extras install nginx1.12
chkconfig nginx on
cd /usr/share/nginx/html
chmod o+w /usr/share/nginx/html
rm index.html
wget https://raw.githubusercontent.com/awsdevopsteam/route-53/master/index.html
wget https://raw.githubusercontent.com/awsdevopsteam/route-53/master/ken.jpg
service nginx start
```

- Review and launch the EC2 Instance

- Once Instance is on, check if the Nginx Web Server is working from the web browser.

- Connect the Nginx Web Server from the terminal with `curl` command.

```bash
curl http://ec2-3-15-183-78.us-east-2.compute.amazonaws.com
```
