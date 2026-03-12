# Day 6 – AWS IAM Least Privilege Lab

## Objective

Implement least privilege access in AWS IAM.

## Steps Performed

1. Created IAM user (grc-test-user)
2. Created custom policy allowing only EC2 DescribeInstances
3. Attached policy to user
4. Verified access restrictions

## Test Results

User could view EC2 instances.
User could not create or delete instances.
User could not access other AWS services.

## Compliance Mapping

Control Type: Preventive Control

Mapped Framework Requirements:
ISO 27001 – Access Control
NIST – Access Management
SOC 2 – Logical Access Control
