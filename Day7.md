# Day 7 - 100 days of DevOps

## Task
- Set up a password-less authentication from user to all app servers 

## Solution
- generate ssh-keygen in user: `ssh-keygen`
- copy public key id to server: `ssh-copy-id tony@stapp01`

## verification
- try to login to server: `ssh tony@stapp01`
