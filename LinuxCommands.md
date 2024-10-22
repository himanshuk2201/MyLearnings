# Linux Commands

- `ls` - list the files and directories in the current directory
	```bash
	ls
	```
- `cd` - change the current directory
	```bash
	cd dir_name
	```
- `mkdir` - create a new directory
	```bash
	mkdir himanshuk
	```
- `rmdir` - remove a directory
	```bash
	rmdir dir_name
	```
- `pwd` - print the current working directory
	```bash
	pwd
	```
- `cp` - copy files or directories
	```bash
	#We will copy a file example.tst from the current directory to backup directory
	cp example.txt backup/
	```
- `mv` - move or rename files or directories
	```bash
	mv example.txt backup/
	```
- `rm` - remove files or directories
	```bash
	rm example.txt
	```
- `touch` - create a new empty file or update the timestamp of an existing file
	```bash
	touch himanshuk.py
	```

- `cat` - concatenate and display files
	```bash
	cat himanshuk.txt
	```
- `man` - manual for a command
	```bash
	man ls
	```
- `htop` - an interactive process viewer and system moniter
	```bash
	htop
	```
- `chmod` - change the permission of a file or directory
	```bash
	# The First digit represents the owner of the file/dir
	# The Second digit represents the group that the file/dir belongs to
	# The third digit represents all other users
	# 0 (no permission)
	# 1 (execute only)
	# 2 (write only)
	# 3 (write and execute)
	# 4 (read only)
	# 5 (read and execute)
	# 6 (read and write)
	# 7 (read, write and execute)
	
	chmod 700 himanshuk.txt
	```
- `chown` - change the owner of the file/dir
	```bash
	chown new_owner himanshuk.txt
	```
- `tar` - create or extract compressed archive files
	```bash
	# x: extract files from an archive
	# t: list the contents of an archive
	# r: append files to an existing archive
	# z: use gzip compression
	# j: use bzip2 compression
	# cf: create file
	# xf: extract file
	
	tar cf archive.tar file1 file2 file3
	```
- `gzip` - compress files
	```bash
	gzip file.txt
	```
- `gunzip` - decompress compressed files
	```bash
	gunzip file.txt.gz
	```
- `ssh` - connect to a remote server securely
	```bash
	ssh username@server_address
	```
- `scp` - securely copy paste files between systems
	```bash
	scp myfile.txt user@removehost:/home/user/
	```
- `ping` - test the network connectivity
	```bash
	ping 000.00.00.00
	```
- `ifconfig` - display or configure network interfaces
	```bash
	ifconfig
	```
- `netstat` - display network connection information
	```bash
	netstat
	```
- `route` - view or configure network routing tables
	```bash
	route [options] [add/delete/show]
	```
- `top` - display system resource usage and processes
	```bash
	top
	```
- `ps` - display information about running processes
	```bash
	ps -ef
	```
- `kill` - terminate a process
	```bash
	kill [PID]
	```
- `systemctl` - control system services
	```bash
	# Start nginx service
	systemctl start nginx

	# Check the status of the nginx service
	systemctl status nginx

	# Stop nginx service
	systemctl stop nginx
	```
- `service` - control system services
	```bash
	service apache2 start
	```
- `useradd` - add a new user
	```bash
	useradd himanshuk
	```
- `passwd` - change the password for a user
	```bash
	passwd new_password
	```
- `userdel` - delete a user from the system
	```bash
	userdel himanshuk
	```
- `su` - switch user to become another user
	```bash
	su himanshuk
	```
- `sudo` - execute a command as another user or with elevated privilages
	```bash
	sudo
	```
- `uptime` - display system uptime and load average
	```bash
	uptime
	```
- `df` - display dish space usage
	```bash
	df
	```
- `du` - display disk usage by file or directory
	```bash
	du
	```
- `mount` - mount a file system
	```bash
	sudo mount /dev/sdb2 /mnt/usb
	```
- `unmount` - unmount a file system
	```bash
	sudo unmount /mnt/usb
	```
- `date` - display or set the system date and time
	```bash
	date
	```
- `whoami` - display the current user name
	```bash
	whoami
	```
- `which` - locate a program or command in the system path
	```bash
	which ls
	```
- `finger` - display system information
	```bash
	finger user_name
	```
- `uname` - display system information
	```bash
	uname
	uname -a
	```
- `history` - display a list of previously executed commands
	```bash
	history
	```
- `echo` - display text or variables to the console
	```bash
	echo 'text goes here.'
	```
- `tee` - redirect output to both a file and the console
	```bash
	ls | tee file.txt
	```
- `locate` - locate any file on the system
	```bash
	locate file.txt
	```
- `sort` - sort lines of text on the system
	```bash
	sort file.txt
	```
- `uniq` - remove duplicate lines from a file or input
	```bash
	uniq file.txt
	```
- `head`/`tail` - display the first/last few lines of a file or input
	```bash
	# display first 10 lines
	head file.txt

	# display last 10 lines
	tail file.txt
	```

