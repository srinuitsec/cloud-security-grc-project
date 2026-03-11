# Day 3 – Cloud Security Risk Register

## What is a Risk Register?

A risk register is a document used to track and manage security risks within an organization.

It records risks, their impact, likelihood, and mitigation actions.

## Risk Register Fields

Risk ID
Risk Description
Asset/System
Threat
Vulnerability
Likelihood
Impact
Risk Level
Mitigation
Risk Owner
Status

## Example Cloud Security Risk Register

| Risk ID | Description | Asset | Likelihood | Impact | Risk Level | Mitigation | Status |
|--------|-------------|-------|-----------|--------|-----------|-----------|--------|
| CR001 | Public S3 bucket | Cloud Storage | High | High | Critical | Disable public access | Open |
| CR002 | Excess IAM permissions | IAM | Medium | High | High | Apply least privilege | Open |
| CR003 | Open firewall rule | VPC Security Group | Medium | Medium | Medium | Restrict access ports | Open |

## Risk Control Mapping

Public cloud storage exposure → Access control and encryption

Weak IAM permissions → Least privilege implementation

Open firewall rules → Network segmentation
