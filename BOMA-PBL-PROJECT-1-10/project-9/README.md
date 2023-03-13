## PBL-Project-9 

# TOOLING WEBSITE DEPLOYMENT AUTOMATION WITH CONTINUOUS INTEGRATION. INTRODUCTION TO JENKINS

This project introduces us to Continuous Integration and continuous Delivery (CI/CD), why there are many CICD tool, but in this project we will be using JENKINS.

**Note:** This project is a continuation of project 8, this means that project 8 must be up and running well before I can implement project 9. The diffrence is that I am adding CI/CD tool (Jenkins) to project 8. 

The following conditions must be met for project 9 to run:

* Apache (httpd) process is up and running on both web servers

* /var/www directories of the web servers are mounted to /mnt/apps of NFS server

* All necessary TCP/UDP ports are opened on all the servers (3306, 111, 2049, 80)

* Client browsers can access both web servers by their respectiv public IP or public DNS.

**Cloud Infracture for the Project**

* Cloud Platform: AWS

* OS: 3 Red Hat Enterprise Linux 8; 3 Ubuntu 20.04

**Server Applications:**

* Webserver (Red Hat Enterprise Linux 8): 2 Apache2

* Load balancer Server (Ubuntu 20.04): Apache load balancer

* Database server (Ubuntu 20.04): MYSQL

* Storage Server (Red Hat Enterprise Linux 8): NFS server

* CI/CD Server (Ubuntu 20.04): Jenkins

