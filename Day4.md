# Day 4 - 100 days of DevOps

## Task
- Grant executable permissions to the .sh script file for all users.

## Solution
- ssh login to App server 3
- `cd /tmp/`
- `sudo chmod +rx xfusioncorp.sh` (need read permission for sh script)

## verify the changes
- `sudo ls -lh`
