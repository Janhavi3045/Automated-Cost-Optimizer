# Automated-Cost-Optimizer
# Automated AWS Cost Optimizer

## Project Overview
This project automatically reduces AWS EC2 costs by stopping idle EC2 instances and starting them on a schedule.

## AWS Services Used
- Amazon EC2
- AWS Lambda
- Amazon CloudWatch
- Amazon EventBridge
- IAM

## Project Flow

EC2
↓
CloudWatch Alarm
↓
EventBridge
↓
Lambda
↓
Stop EC2

Morning Schedule
↓
EventBridge
↓
Lambda
↓
Start EC2
