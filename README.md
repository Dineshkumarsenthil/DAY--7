# Day-7 (Linux)
---
### Tree Command Installation

#### Update Package List

```
sudo apt update	Update ----> #list of available software/packages

sudo apt install tree ----> #the tree directory visualization tool

tree --version ----> #Show the installed version of the tree tool

tree / ----> #Display the entire filesystem structure in a tree format

tail -f /var/log/syslog	----> #Continuously view new system log messages in real-time
```
---
### Ownership & Permissions Management

####  Ownership & Permissions

```
ls -l projects/app.py ---->#Show current owner, group, and permissions of the file

sudo chown root projects/app.py ----> #Change the file owner to root

sudo chgrp sudo projects/app.py ----> #Change the file group to sudo

chmod u+rwx projects/app.py	----> #Give owner read, write, execute permissions

chmod g+rw projects/app.py ----> #Give group read and write permissions

chmod o+r projects/app.py----> #Give others read permission

chmod 764 projects/app.py ----> #Set permissions: owner (rwx), group (rw), others (r)
```
---
