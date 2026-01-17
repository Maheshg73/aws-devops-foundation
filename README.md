# aws-devops-foundation
AWS DevOps learning journey – Week 1 foundation
# Week 1 – AWS DevOps Foundation

## Overview
This project covers basic AWS and Linux operational tasks performed as part of a DevOps learning foundation. The objective was to understand instance provisioning, service management, and basic incident recovery.

## Architecture
- AWS EC2 (Ubuntu)
- Security Group allowing SSH (22) and HTTP (80)
- Nginx web server

## Tasks Performed
- Created an AWS EC2 instance
- Connected securely using SSH
- Installed and configured Nginx
- Verified web access via public IP
- Managed Nginx service (start, stop, restart)
- Simulated service outage and restored availability

## Failure Simulation & Recovery
Nginx service was intentionally stopped to simulate an outage. Service status was verified, root cause identified, and service restarted to restore application availability.

## Key Learnings
- Basics of EC2 provisioning and access
- Linux service control using systemctl
- Importance of monitoring and quick recovery
