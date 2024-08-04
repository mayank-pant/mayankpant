inside vpc there are isolated network in different CIDR ranges called subnets
subnets is used to improve effeciency and security of
public subnect and privae subnet
you can assign CIDR ranges to each of the subnet
you have to have subnet to launch ec2 instances or use most aws resources

security group acts as a virtual firewall to control incoming and outgoing traffic

to allow internet access to your subnect we need a gateway, we need internet gateway
gateway connect your VPC to another network
there are multipe types of gateway like internet gateway, NAT gateway
QUES - gatway only connects to VPC or it can connect specifically to subnect

after setting up gayeway too still VPC will not be able to connect to internet
we need route tables, route tble control the source and destination of traffic
vpc by default has a route table for local traffic betwen the locla subnets
we want to create route table for public subnect and pvt subnect to be able to conect to internet

launch ec2 instances in prvate subnect

NAT gateway is sued to connect t outside VPC. but external services cannot connect to pvt subnet
NAT gateway is created in public subnet beacuse generally public subnect has route out to internet
add NAT gateway connectivity to private subnect route table

NACL - virtual firewall that protects subbnect, it is stateless

security group is a virtual ffirewall that protects ec2, it is statefull

what is security group
what is ssh
what is scp
what is elastic IP
what s transit gateway
what is VPC peering



EC2
HA arctecture
AWS iAM
VPC
rouye 53
s3
kinesis
sqs, sns, ses
alb, elb
database in aws