1>> Networking & Subnetting (AWS VPC Setup)Task 
.
I have created VPC in Region Asia Pacific(Mumbai).I designed the VPC using a 10.0.0.0/16 CIDR block. Inside the VPC, I created 4 subnets,Two of these are public subnets (10.0.0.0/20 and 10.0.16.0/20) while the other two are private subnets (10.0.128.0/20 and 10.0.144.0/20). A public route table directs outbound traffic to the Internet Gateway, and each private subnet uses a NAT Gateway placed in a public subnet to securely access the internet. 
