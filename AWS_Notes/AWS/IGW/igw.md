## Internet gateway basics
To use an internet gateway, you must attach it to a VPC and configure routing.

### Routing configuration
If a subnet is associated with a route table that has a route to an internet gateway, it's known as a public subnet. If a subnet is associated with a route table that does not have a route to an internet gateway, it's known as a private subnet.

In your public subnet's route table, you can specify a route for the internet gateway to all destinations not explicitly known to the route table (0.0.0.0/0 for IPv4 or ::/0 for IPv6). Alternatively, you can scope the route to a narrower range of IP addresses; for example, the public IPv4 addresses of your company’s public endpoints outside of AWS, or the Elastic IP addresses of other Amazon EC2 instances outside your VPC.

<img width="486" height="511" alt="image" src="https://github.com/user-attachments/assets/a6baa2c5-b13b-411f-93cd-0c7019172a07" />
