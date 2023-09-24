# conflicting_private_zones

Provision private AWS Route53 zones with a root and overlapping subdomain attached to a VPC with a 10.0.0.0/16 CIDR with records assigned to a private IP of an EC2 Instance:


```
zone = example.com
record = test.example.com
target = ec2_instance_private_ip

zone = another.example.com
record = test.another.example.com
target = ec2_instance_private_ip
```
