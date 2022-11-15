# AWS-CloudFormation-Templates
AWS CloudFormation Templates

The objectives of this templates are divided into 2 sections:

- Describe a Stack in Cloud Formation that includes an EC2 instance that can be accessed
by SSH from the outside, an instance on EC2 that has a web server where it displays
some feature of the machine and can only be accessed by SSH from the previous instance
EC2, security groups, and required key pairs.

- Describe a Stack in Cloud Formation that includes two EC2 instances with a web server
that shows a similar page but can be recognized as a different server. The
page has to show some feature of the machine and has to be accessible from
outside. A Load Balancer that distributes the requests between the two servers equally and
an “Auto-Scaling Group” that has a minimum of one instance and a maximum of two. The ASG must
be added to the previously described load balancer.
