# Linux
Linux Commands


chmod +x run.sh  -- to make it executable script

=================================

install net-tools and ssh setup in ubuntu

=================================

sudo apt-get install net-tools -y

sudo apt-get install -y openssh-server

nano /etc/ssh/ssh_config (update /etc/ssh/ssh_config file --> Password Authentication no to Password Authentication yes)

systemctl enable ssh --> to start service when machine starts

systemctl start ssh --> to start the service

sudo ufw allow 22 --> to allow 22 port in firewall

sudo ufw allow ssh --> to allow ssh in firewall

=================================
