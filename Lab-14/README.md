## Load Balancing using Application Load Balancer (AWS)
Overview
This lab demonstrates how to configure an Application Load Balancer (ALB) in AWS to distribute traffic across multiple EC2 instances, implement health checks, and integrate Auto Scaling for high availability.

## Objectives

Distribute traffic across multiple EC2 instances
Configure and test health checks
Ensure high availability under failure conditions
Implement Auto Scaling with Load Balancer


## Architecture
User → Application Load Balancer → Target Group → EC2 Instances
                                      |
                                      → Auto Scaling Group


## Setup Summary

Created 2 EC2 instances running Apache web server
Configured security groups for ALB and EC2
Created a target group and registered instances
Configured Application Load Balancer (HTTP:80)
Verified load balancing using ALB DNS

## Lab Tasks
1. Stop One Instance

One EC2 instance was stopped
ALB removed it from traffic automatically
Traffic continued to healthy instance

✅ Demonstrates fault tolerance & high availability

2. Modify Health Check Path

Changed path from /health.html to /wrong.html
All instances became unhealthy
Restored path → instances became healthy again

✅ Demonstrates importance of correct health checks

3. Auto Scaling Group

Created Launch Template and ASG
Attached ASG to target group
ASG launched instances automatically
Terminated one instance → ASG replaced it

✅ Demonstrates automatic scaling & recovery

## Key Learnings

ALB distributes traffic only to healthy targets
Health checks determine instance availability
ALB ensures service continues during failures
Auto Scaling maintains required number of instances
