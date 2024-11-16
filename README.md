# AWS Cloudformation example for Weighted Target Groups
This is a simple Cloudformation template example that allows to test the Weighted Target Groups feature in ALB.

Import the `template.yaml` file in the your AWS account as a new stack, specifying two public subnets and a VPC.

You can test this by making a http request to the DNS generated in the ALB configuration.

Originally made for this article: https://medium.com/@lscicatelli/a-b-testing-using-aws-application-load-balancer-weighted-target-groups-db39e70ca7bd
