# Welcome to Globechain Maintenance Website!

Only one html file. 
Checkout startup script for Google Cloud:
    sudo apt-get update
    sudo apt-get install -y apache2
    sudo apt install -y git
    sudo rm -f /var/www/html/index.html
    sudo git clone https://gitlab.com/globechain/globechain-maintenance.git /var/www/html
    GIT_SSH_COMMAND="ssh -i ~/.ssh/id_rsa" git pull
    