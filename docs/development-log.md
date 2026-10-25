# Development Log

## Stage 1 - VPC Foundation

### Implemented
- Created the initial CloudFormation YAML template.
- Defined the VPC CIDR block as 172.16.0.0/16.
- Enabled DNS support and DNS hostnames.
- Added a Name tag to the VPC.

### Outstanding
- Create public and private subnets.
- Configure internet connectivity.
- Add security groups and EC2 instances.

### Validation
- Pending template validation.
- Deployment not yet performed.

## Stage 2 - Add public and private subnets

### Implemented
- Create public and private subnets.

### Outstanding

- Configure internet connectivity.
- Add security groups and EC2 instances.

### Validation
- Pending template validation.
- Deployment not yet performed.

## Stage 3 - Configure the IGW, public route table and subnet associations

### Implemented
- Configure internet connectivity.

### Outstanding

- Add security groups and EC2 instances.

### Validation
- Pending template validation.
- Deployment not yet performed.

## Stage 4 - Add the bastion EC2 instance and SSH security controls

### Implemented
- Add security groups and EC2 instances.

### Outstanding

- Add two application EC2 instances and their security groups.

### Validation
- Pending template validation.
- Deployment not yet performed.

## Stage 5 - Add two application EC2 instances and their security groups

### Implemented
- Add two application EC2 instances and their security groups.

### Outstanding

- Validate the template & deploy

### Validation
- Pending template validation.
- Deployment not yet performed.

## Stage 6 - Deployment of template in VS code

### Implemented
- After validating the template and deploying, requires pending validation compelted with resources in AWS.
- AWS shows resources created with correct networking as per the deployed code.

### Outstanding

### Validation
- Template validated.
- Deployment successful in AWS.