# msk-lambda-sam

This is SAM template that deployed three Cloudformation stacks

1. VPC with two private subnets, one public subnet
2. MSK Cluster with no auth enabled and VPC endpoints for STS and Lambda
3. VPC attached lambda functions with Amazon MSK as Event Source
