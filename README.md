# VPC-with-servers-in-private-subnets-and-NAT

Implementation of #VPC with servers in private subnets and NAT used in Production environment.

✅ Things Done:

1. To improve resiliency, deployed the servers in two Availability Zones, by using an Auto Scaling group and an Application Load Balancer. </br>
2. For additional security, deployed the servers in private subnets. The servers receive requests through the load balancer. </br>
3. The servers can connect to the internet by using a NAT gateway. To improve resiliency, deploy the NAT gateway in both Availability Zones. </br>
