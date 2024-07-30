#--- Enable SSH

#Install the SSH package.
apt install openssh-server

#Confirm SSH is running after installation.
systemctl status ssh

#If SSH is not running after installation, run the command:
service ssh start
#The above allows you to connect to the Linux server from a remote client.

#To use your local Linux server to SSH into a remote device, install the SSH Client service.
apt install openssh-client

#SSH to the remote device with the following syntax:
ssh userName@IPAddress
