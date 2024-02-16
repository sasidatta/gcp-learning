# WEB server setup 

Once the user created and can login to VM using Putty or Terminal using external ipaddress

Format: ssh username@ipaddress.

eg: ssh dattu@10.198.34.59


# Install nginx web page 


sudo apt-get update

sudo apt install nginx -y 

sudo nginx -v

#install net-tools 
sudo apt install net-tools -y 

#Check if nginx running in port 80
sudo netstat -anopt | grep -i 80

check the external ip browser if you are able to access web page with IP address

curl http://192.18.19.10:80


# Update default web page 

cd /var/www/html

ls 

mv index-debian.html /tmp

gedit index.html 

Check if the changes are reflecting the in web page with url on a browser.

curl http://192.18.19.10:80