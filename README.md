# 



**## Completed Projects**

* [SOC Fundamentals](./SOC-Fundamentals) - Foundations of SOC operations, including the "Three Pillars" (People, Process and Technology) and security frameworks like MITRE ATT\&CK.\*\*
* [SOC L1 Alert Reporting](./SOC-L1-Alert-Reporting) - Hands-on experience with SIEM alert triage and incident reporting.
* [SIEM dashboard Analysis](./SOC-L1-Alert-Reporting/SIEM-Investigation-Analysis.png)
* [AWS EC2 Ubuntu Web Server](./AWS-EC2_Ubuntu_Web_Server_Apache_Deployment) - This project showcase the deployment of a web server on AWS EC2 using Ubuntu and Apache, including network configuration and basic cloud infrastructure setup.

* ## Objectives

- Deploy an Ubuntu EC2 instance on AWS

- Configure security groups and network access

- Install and run Apache web server

- Test web server accessibility via public IP

- Understand basic cloud infrastructure deployment

## Technologies Used

- Amazon Web Services (AWS EC2, VPC, Security Groups)

- Ubuntu Linux

- Apache HTTP Server

- SSH (Secure Shell)

- Networking (Route Tables, Internet Gateway)
 
## Architecture Overview

The project follows a simple cloud architecture:

- **EC2 Instance (Ubuntu):** Hosts the web server  

- **Security Group:** Controls inbound traffic (SSH, HTTP)  

- **VPC & Subnet:** Provides networking environment  

- **Internet Gateway:** Enables internet access  

- **Apache Server:** Serves web content over HTTP  

## Implementation Steps

### 1. EC2 Instance Setup

- Launched an Ubuntu EC2 instance on AWS

- Generated and configured SSH key pair for secure login

- Assigned a public IPv4 address

### 2. Security Group Configuration

- Allowed inbound SSH (port 22) from my IP

- Allowed HTTP (port 80) from anywhere (0.0.0.0/0)

### 3. Server Setup
- Connected to the EC2 instance via SSH
- Installed Apache Web server using:
  sudo apt update
  sudo install apache2 -y
- Connected to EC2 instance via SSH
  
4. Web Server Testing

Attempted access via browser using EC2 public IP address

Internal server functionality was confirmed successfully

External access testing was used to evaluate network accessibility and configuration

Challenges Faced:

- Initial difficulty accessing the web server via browser

- Troubleshooting involved checking:

- Security group rules

- Route table configuration

- Apache service status

- Public IP accessibility

Key Learnings:

- AWS EC2 instance provisioning and management

- Linux server administration using Ubuntu

- Web server installation and configuration (Apache)

- Cloud networking concepts (VPC, Subnets, Internet Gateway)

- Basic troubleshooting of cloud infrastructure issues

Project Status:

✔ EC2 instance successfully deployed and configured

✔ Apache web server installed and running

✔ Security groups correctly configured

✔ Network setup completed

⚠ External browser access partially unsuccessful (under troubleshooting)

Author:

Name: Olaniyan Olayinka

Role: Cybersecurity Enthusiast

Focus Areas: SOC Analyst, AWS + Linux 

References

https://docs.aws.amazon.com/ec2/

https://docs.aws.amazon.com/vpc/

https://httpd.apache.org/docs/
https://www.prestashop.com/en

