# AWS CloudFormation Learning

This repository contains AWS CloudFormation templates created while learning Infrastructure as Code.

## Resources Created

- EC2 Instance
- Security Group
- Amazon Linux 2023
- SSH Access
- CloudFormation Outputs

## Deploy

```bash
aws cloudformation create-stack \
  --stack-name ec2-stack \
  --template-body file://templates/ec2.yaml