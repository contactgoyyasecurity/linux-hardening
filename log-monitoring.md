# Log Monitoring

## Authentication Logs

/var/log/auth.log

## Failed Login Attempts

grep "Failed password" /var/log/auth.log

## Review Sudo Activity

grep "sudo" /var/log/auth.log
