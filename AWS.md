# AWS

## EC2 (Elastic Compute Cloud) Service
- Instances:

	Create new instance
	-------------------
	Allows to create a VM or instance
	- AMI (amazon machine image): Linux, macOS, Ubuntu, Windows, Red Hat, ...
	- Architecture: 64-bit (x86), 64-bit (Arm)
	- Instance Type: 
		- compute optimized
		- memory optimized
		- storage optimized
		eg. Familiy t2, c5, t3, t3a, Mac, M7g, ...
		Naming: t2.2xlarge
		m: instance class
		2: generation (aws improves them over time)
		2xlarge: size within the instance class
	- Key pair (login): use a key pair to securely connect to your instance. (.pem, rsa)
	- User Data: run certain commands while creating an instance
	- Security groups: 
		- Acts as a firewall
		- Regulates access to ports
		- Authorised IP range: IPv4 and IPv6
		- Control of inbound network (from other to instance)
		- Control of outbound network (form instance to other)
	- Configure storage: 
	
	--------------------
	
- Availability zones: 
- Region: Instances runs in particular region
- Free Tier: Some limited services for specific time (12 months)
- Elastic IPs: for associating IP to instance (No charges if used)

-SSH

- EC2 sizing and configuration options
	- OS, CPUs, RAM, Storage, Network card, Furewall rules, Bootstrap script

- Classic Ports to know
	22: SSH
	21: FTP
	22: SFTP
	80: HTTP
	443: HTTPS
	
## IAM (Identity & Access Management) Service
- When user created, Access Key ID & Secret Access Key) 
- IAM Groups	
- IAM Roles
- Policies
	- Json doc that define permissions and can be applied to user, groups and role
