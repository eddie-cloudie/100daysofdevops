# Day1 - 100 days of DevOps 

## Task
- Create a user with a non-interactive shell on App Server 3

## Solution
- ssh login to app server 3
	- `ssh banner@stapp03`
	- `enter password`
- add a user with non-interactive shell
	- `sudo useradd -m -s /usr/sbin/nologin javed`
- verify the user
	- `grep javed /usr/passwd`