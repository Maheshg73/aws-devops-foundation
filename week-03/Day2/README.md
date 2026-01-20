# Week 3 Day 2 – Provisioning Script

## Purpose
Automate EC2 server setup in a repeatable manner.

## What This Script Does
- Updates system packages
- Installs Nginx if missing
- Enables and restarts Nginx
- Logs execution details

## Idempotency
Script can be safely executed multiple times without side effects.

## Validation
- Nginx service status verified
- Log file reviewed

## Safety Guards
- Script validates root privileges
- Ensures supported OS before execution
- Prevents accidental misuse

## Configuration Options
- `NGINX_PACKAGE`: Web server package name
- `SERVICE_NAME`: Service to manage
- `WEB_ROOT`: Web root directory
## CI/CD Compatibility
- Runs non-interactively
- Uses explicit exit codes
- Suitable for Jenkins and GitHub Actions
