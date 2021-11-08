# Overview and Thoughts
To enable a fast deployment process, AWS resources will be provisioned using Terraform .  The archicture  compoent to support  resiliency, reliability, scalability, security, load balancing are stated below;
- Public Subnet ( internet facing , Load Balncer is provisioned in this subnet )
- App Subnet 
- Web Subnet.
- Route tables
- Security group 
- NACL
- EC2 , Autoscaling.

Application Deployment will be supported by AWS EC2 User-Data.
AWS userdata is the set of commands/data you can provide to a instance at launch time.


# How to use ths project

## Prequisite 
- Terraform installed
- AWS CLI configured

### STEP 1: clone the project
- git clone https://github.com/aajibad1/SofterWare-DevOps-Challenge.git

### STEP 2: Initiate terrform
- cd to Project 
- terrform init

### STEP 3: Create Resources 
- terraform plan 
- terrfaorm apply --auto-approve



