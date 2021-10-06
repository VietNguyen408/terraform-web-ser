# Terraform Web Server
Set up a web server to handle web traffic using Terraform and AWS
1. Create VPC
2. Create internet gateway
3. Create custom route table
4. Create a subnet
5. Associate subnet with Route Table
6. Create security group to allow port 22,80,443
7. Create a network interface with an IP in the subnet that create in step 4
8. Assign an elastic IP to the network interface create in step 7
9. Create Ubuntu server and install/enable Apache2
