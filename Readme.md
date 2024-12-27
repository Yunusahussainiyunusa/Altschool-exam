# YUNUSA HUSSAINI YUNUSA: ALT/SOE/024/0175
# PUBLIC IP : 13.60.169.117

### This project showcases how to set up a Linux server, install a web server, and deploy a custom HTML landing page.

### STEPS

Signup on AWS (Amazon Web Services).

Used Ubuntu Server 22.04 LTS.

Instance Type: t3.micro 

Allowed inbound traffic:

Port 22: SSH for remote access.

Port 80: HTTP for web server.
Created SSH Access using : ssh -i yunusa.pem ubuntu@13.60.169.117
Installed Apache 2: sudo apt install -y apache2
Created a new index.html file and edited it : sudo nano index.html
Then I restarted the Apache: sudo service apache2 restart
Then I verified the HTTPS by visiting my public ip.