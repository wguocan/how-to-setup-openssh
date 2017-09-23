1. Installation of OpenSSH in Linux
	On Ubuntu/Debian/Linux Mint:		sudo apt-get install openssh-server openssh-client
	On RHEL/Centos/Fedora:				sudo yum -y install openssh-server openssh-client

2. Configuration of OpenSSH
	server: /etc/ssh/sshd_config
	client: /etc/ssh/ssh_config

3. Start and Enable ssh-server
	sudo service sshd start

4. Verify OpenSSH Server
	nc -v -z 127.0.0.1 22
	result: Connection to 127.0.0.1 22 port [tcp/ssh] succeeded!
