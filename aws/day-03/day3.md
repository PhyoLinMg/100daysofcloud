# AWS - Day 3

## Create Subnet

Try to consider the following points before creating Subnet

Go to VPC

VPC -> Subnets

VPC 172.31.0.0/16


172.31.0.0/20
172.31.16.0/20
172.31.32.0/20
172.31.48.0/20
172.31.64.0/20
172.31.80.0/20(20 bit used)

32 bits total
4 outlet - 32/4 = 8


00000000.00000000.00000000.00000000
172      .31       .0        .0


Network Address needed to be used
(1 represents the network address)(0 represents the host address)
11111111.11111111.1111 0000.00000000



2 power 4 = 16

2 power 12= 4096

First address: Network Address
Last address: Broadcast Address
AWS reserved 3 Addresses

Usage IP: 4096 - 2 - 3 = 4091


## Steps
Search for Subnets.Click on VPC feature Subnet.
And Click on Create Subnet. 

For ipV4 subnet CIDR block, use the one that is available. You can refer to the subnet list that they have done. Choose the free one and click on Create Subnet.

