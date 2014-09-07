# LAMP Stack Provisioning Example Commands

### Part 1 Commands

	pwd
	cd vagrant/
	ls
	git init
	git add .
	git status
	git commit -m "initial commit"
	git remote add origin git@github.com:screencasts-pro/vagrant.git # use your own repository
	git push -u origin master
	cd scripts/
	ls
	mate centos-lamp.sh # write shell provisioning script
	cd ..
	cd files/
	pwd
	ls
	mate index.html # create simple webpage
	mate info.php # create php file to call phpinfo()
	cd ..
	pwd
	git status
	git add .
	git status
	git commit -m "adding files for LAMP stack"
	git push origin master # -u is not required
	cd scripts/
	mate centos-lamp.sh # configure to download index.html and info.php from GitHub
	cd ..
	pwd
	git status
	git commit -am "Updated LAMP script with GitHub files"
	git push origin master
	cd
	clear

### Part 2 Commands

	cd projects/
	git init shell-lamp
	cd shell-lamp/
	pwd
	vagrant box list
	vagrant init chef/centos-6.5
	mate Vagrantfile # enable port forwarding, disable vbguest update, add file and shell provisioners
	echo ".vagrant" >> .gitignore
	git add .
	git commit -m "initial commit"
	clear
	ls
	ls -al
	clear
	vagrant up # notice problem
	mate Vagrantfile # fix problem
	clear
	vagrant up
	ls
	mate index.html # make changes
	vagrant destroy
	clear

### Notes




