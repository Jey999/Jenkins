# Testing 1
# Testing 2

VPC - virtual private cloud, This is an isolated network within our region.

After creating a VPC we can add one or more subnets in each availability zone.

Subnet - Is the process of dividing a network into two or more networks.

In order for the subnets to communicate they need to be in the same network

Security Group - A security group acts as a virtual firewall for your instance to control inbound and outbound traffic
 <!-- Here we can create a public and private SG's and specify it's corresponding inbound and outbound rules for each group. This applies at instance level . -->

 Security groups act at the instance level, not the subnet level. Therefore, each instance in a subnet in your VPC could be assigned to a different set of security groups.

A network access control list (NACL) -  is an optional layer of security for your VPC that acts as a firewall for controlling traffic in and out of one or more subnets. You might set up network ACLs with rules similar to your security groups in order to add an additional layer of security to your VPC

A route table contains a set of rules, called routes, that are used to determine where network traffic from your subnet is directed. Each subnet in your VPC must be associated with a route table, which controls the routing for the subnet.
