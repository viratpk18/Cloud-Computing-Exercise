# Cloud-Computing-Exercise


RDS port kill command
	
	netstat -aon | findstr :3306
	taskkill /PID 1234 /F


EC2 Deploy command
	
	sudo su -
	yum update -y
	yum install -y httpd
	wget https://github.com/viratpk18/portfolio/archive/refs/heads/main.zip
	unzip main.zip
	cp -r portfolio-main/* /var/www/html/
	systemctl enable httpd
	systemctl start httpd
	systemctl status httpd
	curl http://checkip.amazonaws.com
