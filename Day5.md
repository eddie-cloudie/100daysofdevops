## Day 5 - 100 days of DevOps

## Task
- install SELinux package and disable it permanently.
- not require reboot after config

## Solution
- ssh login to app server 3
- install SELinux package
	- `sudo yum install -y selinux-policy selinux-policy-targeted policycoreutils`
- diable SELinux
	- `sudo vi /etc/selinux/config
	- `SELINUX = disabled`
- verify status
	- `sudo sestatus
