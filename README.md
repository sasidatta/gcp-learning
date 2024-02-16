# gcp-learning
Google cloud learning


SSH - password based 

Public key auth 



#https://www.digitalocean.com/community/tutorials/how-to-create-a-new-sudo-enabled-user-on-ubuntu-22-04-quickstart

# Add new user 
adduser dattu


#Add to sudo group
usermod -aG sudo dattu

#https://serverpilot.io/docs/how-to-enable-ssh-password-authentication/
vi /etc/ssh/sshd_config

systemctl restart sshd



CUstom VM

