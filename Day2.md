\# Day 2 - 100 Days of DevOps



\## Task

* Create a user (mark) with expiry date (2026-12-07) on app server 3



\## Solution

* ssh login to app server 3

&#x09;- `ssh banner@stapp03`

&#x09;- `enter password`

* add a user with expiry date

&#x09;- `sudo useradd -e "2026-12-07" mark`

* verify the user

&#x09;- `sudo chage -l mark`

