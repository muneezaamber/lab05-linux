## Question 1
Answer: I am muneezaamber. My home folder is /home/muneezaamber.
Commands: whoami, pwd

## Question 2
Answer: The server's name is ubuntu, and it runs Ubuntu 26.04.1 LTS.
Commands: hostname, cat /etc/os-release | head -2

## Question 3
Answer: The server has 1.6Gi of total RAM, and about 2.6G of free disk space on the root drive.
Commands: free -h, df -h /

## Question 4
Answer: Users with /bin/bash access include root and muneezaamber.
Command: grep bash /etc/passwd

## Question 5
Answer: There are around 220 processes running right now.
Command: ps aux | wc -l

## Question 6
Answer: lab5user was created and removed today (see auth.log for exact timestamps).
Command: sudo grep lab5user /var/log/auth.log
