# assume-role-identity
Replace Access and Secret Key use in Jenkins by Role-Based apporach. 

Deploy jenkins server on EC2
Attach a role to it. 
Create an Role for jenkins with access: 
AdministratorAccess
AmazonEC2ReadOnlyAccess
AmazonS3FullAccess
ReadOnlyAccess
Also provide route53 access. 

Create EMR/ec2 template using Terraform module. 

