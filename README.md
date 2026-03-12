# AWS Security Monitoring with Terraform

## Overview

This project deploys an automated AWS security monitoring system using Terraform.

The infrastructure includes:

- AWS GuardDuty for threat detection
- AWS CloudTrail for API activity logging
- Secure S3 bucket for log storage
- SNS alerts for security notifications
- CloudWatch Event Rules to trigger alerts

This project demonstrates Infrastructure as Code (IaC) and AWS security best practices.

---

## Architecture

(Add architecture screenshot here)

![Architecture](images/architecture.png)
GuardDuty Threat Detection Dashboard

This screenshot shows the Amazon GuardDuty console displaying security findings detected in the AWS account. 
GuardDuty continuously monitors the environment for suspicious activity and generates alerts that are sent to SNS.

[Image appears here]

---

## Security Features

- S3 bucket encryption (AES256)
- S3 public access blocked
- S3 versioning enabled
- GuardDuty threat detection
- CloudTrail API logging
- SNS real-time security alerts

---

## Terraform Resources Created

- S3 Bucket (Secure Log Storage)
- CloudTrail Trail
- GuardDuty Detector
- SNS Topic
- CloudWatch Event Rule
- CloudWatch Event Target

---

## Deployment Steps

```bash
terraform init
terraform plan
terraform apply
