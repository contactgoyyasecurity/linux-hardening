# User Account Security

## Review Users

cat /etc/passwd

## Check Sudo Users

getent group sudo

## Lock Unused Accounts

sudo usermod -L username
