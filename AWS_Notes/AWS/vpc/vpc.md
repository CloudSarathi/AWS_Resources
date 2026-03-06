# Virtual Private Cloud (VPC)

### Why VPC

<img width="874" height="390" alt="image" src="https://github.com/user-attachments/assets/c2974d58-7c30-4ad2-8bda-3051fe4394b0" />

- Who can Access the application and
database ?
- Can anyone from internet directly connect
to the database ?

How do we create your own Private Network
in Cloud

### AWS VPC
* It is our own isolated network in AWS cloud
* Network traffic within a VPC is isolated (not visible) from all other Amazon VPCs and other resources in AWS
* We control all the traffic coming in and going outside a VPC
* Create all your AWS resources (compute, storage, databases etc) within a VPC
* Secure resources from unauthorized access AND Enable secure communication between your cloud resources


### AWS VPC CIDR (Classless Inter-Domain Routing) Blocks

Example: Resources inside a specific network can use IP addresses from 69.208.0.0 to 69.208.0.15

* How do you express a range of addresses that resources in a network can have?
* CIDR block
* A CIDR block consists of a starting IP address(69.208.0.0) and a range(/28)

Example: CIDR block 69.208.0.0/28 represents addresses from 69.208.0.0 to 69.208.0.15 – a total of 16 addresses

* Tip: 69.208.0.0/28 indicates that the first 28 bits (out of 32) are fixed.
* Last 4 bits can change => 2 to the power 4 = 16 addresses
