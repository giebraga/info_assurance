# Step-by-Step Documentation
### 1. Prepare and Install Headless Raspbian OS in Raspberry Pi
* First install [Raspberry Pi.](https://www.raspberrypi.com/software/)
### 2. Connecting to Raspberry Pi via SSH using the terminal
* ssh <username>@<hostname>
* sudo apt update
* sudo apt upgrade
### 3. Deploying LAMP (Linux Apache MySQL PHP) Stack in raspberry Pi
* sudo apt install apache2
* sudo apt install mariadb-server
* sudo mysql_secure_installation
* sudo apt install php libapache2-mod-php php-mysql
* sudo apt-get install php*
* sudo apt install phpmyadmin
### 4. Enabling and controlling Raspberry Pi using VNC
* sudo raspi-config
