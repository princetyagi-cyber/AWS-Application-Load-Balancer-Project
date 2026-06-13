# AWS Application Load Balancer Project

## Objective

Distribute incoming traffic across multiple EC2 instances using AWS Application Load Balancer.

---

## Services Used

* AWS EC2
* AWS Application Load Balancer
* AWS Target Group
* AWS Security Group
* Red Hat Linux
* HTTPD Web Server

---

## Step 1 - Launch EC2 Instances

Launch multiple Red Hat EC2 instances.

![EC2](screenshots/ec2-instances.png)

---

## Step 2 - Configure Security Group

Allow HTTP and SSH traffic.

![Security](screenshots/security-group.png)

---

## Step 3 - Install HTTPD Web Server

Install and start HTTPD web server on both EC2 instances.

![HTTPD](screenshots/httpd-install.png)

---

## Step 4 - Create Web Pages

Create custom web pages on both servers.

![Web](screenshots/web-pages.png)

---

## Step 5 - Create Target Group

Create a target group for EC2 instances.

![Target](screenshots/target-group.png)

---

## Step 6 - Register Targets

Register EC2 instances to the target group.

![Targets](screenshots/register-targets.png)

---

## Step 7 - Create Application Load Balancer

Create an Application Load Balancer.

![ALB](screenshots/create-alb.png)

---

## Step 8 - Configure Listener

Configure HTTP listener and forward traffic to target group.

![Listener](screenshots/listener.png)

---

## Step 9 - Verify Load Balancing

Access Load Balancer DNS and verify traffic distribution across EC2 instances.

![Output](screenshots/load-balancer-output.png)

---

# Final Result

Successfully distributed traffic across multiple Red Hat EC2 instances using AWS Application Load Balancer.
