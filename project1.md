## Documentation of Project 1

**Command/Installation performed with output**

`sudo apt update`

`sudo apt install apache2`

![sudo apt update & install apache2](./sudo-app-update.png)

`sudo apt install mysql-server`
![install mysql-server](./sudo-apt-install-mysql-server.png)

`sudo mysql`
![install mysql](./sudo-mysq.png)

`sudo mysql_secure_installation`
![mysql secure insta;lation](./sudo-mysql_secure_installation.png)

`sudo apt install php libapache2-mod-php php-mysql`
![install php](./sudo-apt-install-php.png)

`php -v`
![php -v](./php-v.png)

`sudo mkdir /var/www/projectlamp`

![sudo mkdir](./sudo%20mkdir%20%3Avar.png)

`sudo ls /etc/apache2/sites-available` 
![sudo ls site available](./sudo%20ls%20%3Aetc%3Aapache2%3Asites-available.png)

`sudo echo 'Hello LAMP from hostname' $(curl -s http://169.254.169.254/latest/meta-data/public-hostname) 'with public IP' $(curl -s http://169.254.169.254/latest/meta-data/public-ipv4) > /var/www/projectlamp/index.html`

![hello LAMP](./Hello%20Lamp.png)

`sudo vim /etc/apache2/mods-enabled/dir.conf`
![mods-enabled](./sudo%20vim%20%3Aetc%3Aapache2%3Amods.png)


