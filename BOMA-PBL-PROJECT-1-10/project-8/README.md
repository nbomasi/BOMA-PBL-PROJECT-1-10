## PBL-Project-8

# LOAD BALANCER SOLUTION WITH APACHE

**Note:** This project is a continuation of project 7, this means that project 7 must be up and running well before I can implement project 8. The diffrence is that I am considering 2 web servers instead of 3 and adding apache load balancer so tha a single URL will be use to access the web against the 3 that was used in project 7. 

**The following conditions must be met for project 8 to run:**

* Apache (httpd) process is up and running on both web servers

* /var/www directories of the web servers are mounted to /mnt/apps of NFS server

* All necessary TCP/UDP ports are opened on all the servers (3306, 111, 2049, 80)

* Client browsers can access both web servers by their respectiv public IP or public DNS.

## Cloud Infracture for the Project

Cloud Platform: AWS
OS: 3 Red Hat Enterprise Linux 8; Ubuntu 20.04

## Server Applications:

Webserver (Red Hat Enterprise Linux 8): 2 Apache2
Database server (Ubuntu 20.04): MYSQL
Storage Server (Red Hat Enterprise Linux 8): NFS server