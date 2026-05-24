#  AWS EC2 Windows Server Deployment

##  Project Overview

This project demonstrates the successful deployment and configuration of a Windows-based Amazon EC2 instance using Amazon Web Services (AWS). The goal of this project was to gain hands-on experience with cloud infrastructure, virtual server provisioning, networking basics, and AWS cloud management tools.

The instance was launched in the **US East (N. Virginia) – us-east-1** region using the **t3.micro** instance type under the AWS Free Tier. The project involved understanding instance creation, security settings, public/private networking, monitoring, and instance lifecycle management.

---

#  Services & Technologies Used

* Amazon EC2
* AWS Management Console
* Windows Server
* AWS Free Tier
* Elastic Compute Cloud (EC2)
* Security Groups
* Public & Private IP Addressing
* RDP (Remote Desktop Protocol)
* Cloud Infrastructure Basics

---

#  Project Screenshot

## EC2 Instance Dashboard

<img width="1290" height="567" alt="Screenshot From 2026-05-24 08-41-37" src="https://github.com/user-attachments/assets/d5787549-8a78-41a0-a6e5-4d0ab038b038" />


---

#  Instance Configuration

| Configuration     | Details        |
| ----------------- | -------------- |
| Instance Name     | Windows-EC2    |
| Instance Type     | t3.micro       |
| Operating System  | Windows Server |
| Region            | us-east-1      |
| Availability Zone | us-east-1d     |
| Instance State    | Running        |
| Status Checks     | 3/3 Passed     |
| Access Method     | RDP            |
| Cloud Platform    | AWS EC2        |

---

#  Steps Performed

##  AWS EC2 Launch

* Logged into AWS Management Console
* Navigated to EC2 Dashboard
* Selected “Launch Instance”

##  Operating System Selection

* Chose Windows Server AMI
* Selected Free Tier eligible instance type (t3.micro)

##  Key Pair Creation

* Generated a secure key pair for remote access authentication
* Downloaded private key securely

##  Security Group Configuration

Configured inbound traffic rules:

* RDP (Port 3389) → Remote Windows access
* HTTP (Port 80) → Web traffic access
* HTTPS (Port 443) → Secure web traffic

##  Instance Deployment

* Launched the EC2 instance successfully
* Verified instance state as “Running”
* Checked health monitoring and status checks

##  Networking & Monitoring

* Explored public and private IP configurations
* Reviewed networking details and security settings
* Monitored instance health using AWS dashboard

---

#  Networking Concepts Learned

## Public IP Address

Used for internet communication and remote access from external networks.

## Private IP Address

Used for internal communication inside the AWS VPC network.

## Security Groups

Acted as virtual firewalls controlling inbound and outbound traffic.

## Availability Zone

Understood high availability concepts using AWS Availability Zones.

---

#  Key Learning Outcomes

 Learned how cloud virtual servers are provisioned in AWS
 Understood EC2 instance lifecycle states
 Explored AWS networking fundamentals
 Practiced configuring security groups and remote access
 Learned public vs private IP communication
 Improved familiarity with AWS Console navigation
 Understood monitoring and instance health checks
 Gained foundational cloud infrastructure knowledge

---

#  Security Practices Followed

* Restricted inbound access using Security Groups
* Used key-based authentication for secure access
* Avoided exposing unnecessary ports publicly
* Monitored instance health and accessibility

---

#  Future Enhancements

* Deploy a live website on EC2
* Configure Load Balancer
* Set up Auto Scaling
* Integrate CloudWatch monitoring
* Practice Infrastructure as Code using Terraform
* Configure custom VPC networking
* Dockerize applications on EC2

---

#  Real-World Relevance

Amazon EC2 is widely used in production cloud environments for:

* Web hosting
* Application deployment
* Virtual machines
* Scalable backend systems
* Enterprise cloud infrastructure

This project provided practical exposure to industry-standard cloud engineering workflows.

---

#  Author

## Gokul M

Aspiring Cloud Engineer | AWS | Linux | Networking | DevOps Learner

### LinkedIn

https://www.linkedin.com/in/gokul-m05/

### GitHub

https://github.com/gokul-dev-ml

---

#  Tags

AWS • EC2 • Cloud Computing • Windows Server • AWS Free Tier • Cloud Engineering • Networking • Infrastructure • DevOps • Linux • Cloud Projects

