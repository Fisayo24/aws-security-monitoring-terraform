# AWS Security Monitoring with Terraform

This project deploys a security monitoring environment in AWS using Terraform.

## Services Used

- Amazon GuardDuty
- AWS CloudTrail
- Amazon SNS
- Amazon S3

## GuardDuty Dashboard

![GuardDuty Dashboard](images/guardduty-dashboard.png)

## Description

GuardDuty monitors AWS accounts for suspicious activity while CloudTrail logs API activity.  
SNS sends alerts when security findings are detected, and S3 securely stores logs.
