# MagicOnlineMachine 
## Objectives
- Create: Cloudformation templates and scripts needed to deploy a windows EC2 instance, obtain password, and shutdown windows EC2.
  - Cloudformation template provisioning resources:
	- VPC or BYO-VPC w/ appropriate subnet
		- Subnet
		- Route Table
		- Routes
    - EC2 Instance
  - Scripts
	- Makefile
		- Deploy templates.
		- Fetch exports
		- Fetch password data 
		- Fetch hostname
	- Testing
	- CI
