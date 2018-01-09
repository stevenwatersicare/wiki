## Checking out and Installing Ospre 2.0


### Install Apache 

### Install PHP 5

https://linuxhint.com/install-php5-ubuntu/

### Create a sybolic link for the YII framework (if you have in a different directory other then Apache's www/html directory)

`sudo ln -s /home/steven/Development/Web/PHP/yii /var/www/html/yii`

Change owner ship of the yii directory that was created from the above command: 

`sudo chown www-data -R /var/www/html/yii/`

Make sure you own all of the development files. 

## Create an empty optimart_ospre database

While logged in as root... mysql -u root -p 


sudo apt-get install php5.6-mbstring

sudo apt-get install php5.6-mysql


`GRANT USAGE ON *.* TO 'steven'@'%' IDENTIFIED BY PASSWORD 'your password here'`

`GRANT ALL PRIVILEGES ON optimart_ospre.* TO 'your user name'@'%'`

Create devbox user and webdev and grant all privileges to devbox user.

`GRANT USAGE ON *.* TO 'devbox'@'%' IDENTIFIED BY PASSWORD '*2ED56AB5389B67679A4EF5568CA5E5E30E368D04';`

`GRANT ALL PRIVILEGES ON optimart_ospre.* TO 'your user name'@'%'`

`GRANT ALL PRIVILEGES ON optimart_timeclock.* TO 'steven'@'%';`

SELECT * FROM information_schema.user_privileges;

SHOW GRANTS FOR steven;

SHOW GRANTS FOR CURRENT_USER();

SELECT Password('webdev');

## Create an empty optimart_timeclock database


## Setup Phinx 

compuster install

add Phinx.yaml file to the vendor/robmorgan/phinx directory



### Create Necessary Directories
`steven@steven-work:~$ sudo mkdir -p /home/steven/Development/Web/PHP/ospre2.0/branches/contact.pricing.page.project.steven.20171127/protected/runtime`

`steven@steven-work:~$ sudo mkdir -p /home/steven/Development/Web/PHP/ospre2.0/branches/contact.pricing.page.project.steven.20171127/assets`