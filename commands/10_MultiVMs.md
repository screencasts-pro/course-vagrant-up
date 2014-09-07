# Multiple Virtual Machines Commands

### Commands

	pwd
	cd vagrant/
	cd scripts/
	ls
	mate centos-lamp.sh
	mate centos-common.sh
	mate centos-lamp.sh
	mate centos-web.sh
	mate centos-database.sh
	ls
	cd ..
	git add .
	git status
	git commit -m "Adding files for multi-vm setup"
	git push origin master
	clear
	cd projects/
	git init multi-vms
	cd multi-vms/
	cp ../shell-lamp/Vagrantfile .
	ls
	mate Vagrantfile # configure scripts for multi-vm setup
	git status
	git add .
	git commit -m "initial commit"
	clear
	vagrant up web
	vagrant status
	vagrant up db
	vagrant status
	vagrant status web
	clear
	vagrant halt db
	vagrant halt web
	vagrant status
	vagrant up # brings up both
	clear
	vagrant ssh web
	ifconfig | grep inet
	ssh 192.168.10.3
	ifconfig | grep inet
	exit
	clear
	nc -z -w1 192.168.10.3 3306
	exit
	vagrant halt
	cd


### Notes




