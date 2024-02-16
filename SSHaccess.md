# SSH Authentication

By default password based SSH authentication disabled inside a VM.

This can be changed with below instructions

Documentation

https://serverpilot.io/docs/how-to-enable-ssh-password-authentication/

Update the ssh config file as below 

gedit /etc/ssh/sshd_config    ( or vi /etc/ssh/sshd_config )

Update the passwordAuth field to yes 

PasswordAuthentication yes

Restart the SSH service after this changes 
systemctl restart sshd

# Create a linux user 

#https://www.digitalocean.com/community/tutorials/how-to-create-a-new-sudo-enabled-user-on-ubuntu-22-04-quickstart

# Add new user 
adduser dattu


# Add to sudo group
usermod -aG sudo dattu