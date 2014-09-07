# Plugins Commands

### Commands

	pwd
	cd projects/
	mkdir baked-lamp
	cd baked-lamp
	vagrant init chef/centos-6.5
	mate Vagrantfile # enable port forwarding
	vagrant ssh # enter VM
	clear
	sudo yum update -y
	clear
	sudo yum install -y nano git unzip screen
	clear
	sudo yum install -y httpd httpd-devel httpd-tools
	clear
	sudo chkconfig --add httpd
	sudo chkconfig httpd on
	sudo service httpd stop
	cd /var/www/html
	ls
	cd ..
	ls
	sudo rm -rf html
	ls
	sudo ln -s /vagrant /var/www/html
	exit
	ls
	mate index.html
	ls
	pwd
	vagrant ssh # back into VM
	sudo service httpd start
	exit
	vagrant ssh
	clear
	sudo yum install -y php php-cli php-common php-devel php-mysql
	sudo service httpd restart
	exit
	pwd
	mate info.php
	ls
	vagrant ssh
	clear
	sudo yum install -y mysql mysql-server mysql-devel
	sudo chkconfig --add mysqld
	sudo chkconfig mysqld on
	sudo service mysqld start
	mysql -u root -e "CREATE DATABASE IF NOT EXISTS dev_test";
	mysql -u root -e "SHOW DATABASES";
	exit
	vagrant help package
	vagrant status
	vagrant package --output centos-lamp.box
	clear
	ls
	vagrant box add centos-lamp centos-lamp.box
	cd ..
	clear
	mkdir test-lamp
	cd test-lamp/
	vagrant box list
	vagrant init centos-lamp
	mate Vagrantfile
	clear
	vagrant plugin install vagrant-vbguest
	clear
	vagrant up
	ls
	mate index.html

### Notes




