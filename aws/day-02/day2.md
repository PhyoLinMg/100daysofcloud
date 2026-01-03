# AWS - Day 2

## Create Security Group

## Details 
Security Group
- Instance level Firewall
- Works at EC2/ENI Instance Level
- Stateful -> If you allow inbound traffic, it will allow outbound traffic
- Rules: Allow Only
- Common Use: Control Access to EC2 Instances, Load Balances, RDS, EKS nodes
- Easy to manage for application level traffic

NACL
- Subnet-level Firewall
- Stateless -> need to allow both inbound and outbound traffic
- Rules: Allow+Deny
- Evaluated in order
- Good for blocking specific IPs or enforcing subnet-level boundaries


## Steps
Login to the AWS Console provided by the document.

After logging in, search for security groups and click on it.

Click on create security group.

Name - given in document
Description - given in document
VPC - default VPC

Create two inbound rule

1. Type - HTTP, Source - Anywhere ipv4(Ports and protocols can be used as default)
2. Type - SSH, Source - Anywhere ipv4(Ports and protocols can be used as default)