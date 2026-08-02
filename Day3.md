# Day 3 - 100 days of DevOps

## Task
- Disable direct SSH rootlogin on all app servers

## Solution
- ssh login to app servers
- modify ssh config
	- Open editor: `sudo vi /etc/ssh/sshd_config`
	- change to `PermitRootLogin no`
	- save config `:wq`
	- restart ssh service `sudo systemctl restart sshd`
- verify changes
	- `sshd -T | grep permitrootlogin`
