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

### Directories & Files

```
mkdir -p ~/linux_practice/permissions----> #Create permissions directory and (parent dirs if needed)

cd ~/linux_practice----> #Change current directory to linux_practice

mkdir projects config logs---->#Create three directories: projects, config, and logs

touch projects/app.py ---->#

echo "Hello World" > projects/readme.txt ----> #Create an empty file named app.py in projects

mv projects/readme.txt docs_readme.txt ----> #Create a file with text "Hello World" in projects/readme.txt

mv docs_readme.txt config/ ----> #Move docs_readme.txt into the config directory

rm config/docs_readme.txt	----> #Remove (delete) the file docs_readme.txt from config

rmdir logs ----> #Remove the empty directory logs
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
