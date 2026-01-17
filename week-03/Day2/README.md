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
