# Day 6 - 100 Days of DevOps

## Task
- install cronie package on all app servers
- add a cron job for root user

## Solution
- cronie package installation: `sudo dnf install -y cronie`
- enable cronie service: `sudo systemctl enable --now crond`
- add a cron job for root user: `sudo su` `crontab -e` `* * * * * path/to/command`

## verify a cron job
- `crontabl -l`
