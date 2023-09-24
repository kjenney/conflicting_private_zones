# conflicting_private_zones

Provision private AWS Route53 zones with a root and overlapping subdomain attached to a VPC with a 10.0.0.0/16 CIDR with records and targets:

zone = example.com
record = test.example.com
target = 10.0.0.45

zone = another.example.com
record = test.another.example.com
target = 10.0.0.46