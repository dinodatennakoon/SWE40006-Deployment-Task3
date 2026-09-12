# SWE40006 Deployment Task 3

This repository contains the small scripts and commands used for my AWS Deployment Task 3.

## Files

### user-data.sh
Used in the EC2 Launch Template to start and enable Apache automatically when a new Auto Scaling instance is launched.

### backup-restore-commands.txt
Contains the AWS CLI and Linux commands used to create the WordPress file backup, upload it to Amazon S3, download it again, and restore the files.

## AWS Services Used

- Amazon EC2
- Amazon RDS
- Amazon S3
- IAM
- Application Load Balancer
- EC2 Auto Scaling
- Amazon CloudWatch
- Amazon SNS
- AWS Systems Manager Session Manager

No private keys, passwords, database credentials or other sensitive information are included in this repository.
