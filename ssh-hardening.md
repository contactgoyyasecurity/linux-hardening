# SSH Hardening

## Disable Root Login

/etc/ssh/sshd_config

PermitRootLogin no

## Use Key-Based Authentication

PasswordAuthentication no

## Change Default Port (Optional)

Port 2222

## Restrict Users

AllowUsers adminuser
