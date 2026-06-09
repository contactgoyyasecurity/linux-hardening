# Firewall Hardening

## UFW Setup

sudo ufw default deny incoming

sudo ufw default allow outgoing

sudo ufw allow 22/tcp

sudo ufw enable

## Verify Rules

sudo ufw status verbose
