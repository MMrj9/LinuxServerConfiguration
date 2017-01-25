----SSH----
Ip Address: 35.160.16.107
Port: 2200

$ ssh -i ~/.ssh/udacity_key.rsa root@35.160.16.107 -p 2200
-----------

----URL----
ec2-35-160-16-107.us-west-2.compute.amazonaws.com
-----------


----Software Installed and Configurations Changed----
- I added the "user" grader and assign him the password "udacity"
- i edited his permissons using the "visudo" command and by adding the following line to the permissions file "grader ALL=(ALL:ALL) ALL"
- Updated all packages with "sudo apt-get update" and "sudo apt-get upgrade"
- Changed the timezone with "sudo dpkg-reconfigure tzdata"
- Changed the SSH port from 22 to 2200 
- Configured the Uncomplicated Firewall (UFW) to only allow incoming connections for SSH (port 2200), HTTP (port 80), and NTP 
(port 123)
- Installed Apache2
- Installed pythonsetuptools for installing packages and mod wsgi to host python web applications 
- Installed virtuaenv and created a virtual environment "venv" 
- Installed flask using pip
- Configured a new virtual host
- Created catalog.wsgi 
- Installed the sqlalchemy, requests and oauthlib packages
- Installed the postgres connector python-psycopg2
- Installed postgresql 
- Created a user and a database
-----------------------------------------------------

----Third-Party Resources----
- Udacity Discussion Foruns
- Ubuntu Foruns
- Stackoverflow
- Stueken Guide - https://github.com/stueken/FSND-P5_Linux-Server-Configuration
- Digital Ocean - https://www.digitalocean.com/community/tutorials/how-to-secure-postgresql-on-an-ubuntu-vps
------------------------------
