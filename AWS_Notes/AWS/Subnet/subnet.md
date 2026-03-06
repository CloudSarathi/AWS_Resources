## Subnet Basics
Each subnet must reside entirely within one Availability Zone and cannot span zones. By launching AWS resources in separate Availability Zones, you can protect your applications from the failure of a single Availability Zone.

### Subnet IP address range
When you create a subnet, you specify its IP addresses, depending on the configuration of the VPC:

* IPv4 only – The subnet has an IPv4 CIDR block but does not have an IPv6 CIDR block. Resources in an IPv4-only subnet must communicate over IPv4.
* Dual stack – The subnet has both an IPv4 CIDR block and an IPv6 CIDR block. The VPC must have both an IPv4 CIDR block and an IPv6 CIDR block. Resources in a dual-stack subnet can communicate over IPv4 and IPv6.
* IPv6 only – The subnet has an IPv6 CIDR block but does not have an IPv4 CIDR block. The VPC must have an IPv6 CIDR block. Resources in an IPv6-only subnet must communicate over IPv6.

### Subnet types
The subnet type is determined by how you configure routing for your subnets. For example:

* Public subnet – The subnet has a direct route to an internet gateway. Resources in a public subnet can access the public internet.
* Private subnet – The subnet does not have a direct route to an internet gateway. Resources in a private subnet require a NAT device to access the public internet.
* VPN-only subnet – The subnet has a route to a Site-to-Site VPN connection through a virtual private gateway. The subnet does not have a route to an internet gateway.
* Isolated subnet – The subnet has no routes to destinations outside its VPC. Resources in an isolated subnet can only access or be accessed by other resources in the same VPC.
* EVS subnet – This type of subnet is created using Amazon EVS. For more information, see VLAN subnet in the Amazon EVS User Guide.

### Subnet diagram
The following diagram shows a VPC with subnets in two Availability Zones and an internet gateway. Each Availability Zone has a public subnet and a private subnet.

<img width="511" height="401" alt="image" src="https://github.com/user-attachments/assets/52447e47-c70c-4d1a-8d67-e50d46fbbc38" />
