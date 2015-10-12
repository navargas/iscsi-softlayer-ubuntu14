# iscsi-softlayer-ubuntu14
#####Simple script to set up Softlayer iSCSI block storage on Ubuntu 14 machines

### NOTICE
This script is provided without warrenty. I needed something to automate the configuration of
serveral Ubuntu 14 nodes in a cluster of machines hosted on Softlayer. I can't promise that it
will work on your configuration, and I can't imagine it will work if your configuration does not
match mine (softlayer, ubuntu 14.10, iscsi block storage also on softlayer).

### HOWEVER
I couldn't find good documentation for this process online, so feel free to use these files as reference!

### Usage
Step 1:
```
read/understand what this script does before piping into an elevated shell
```
Step 2:
```
curl https://raw.githubusercontent.com/navargas/iscsi-softlayer-ubuntu14/master/run | bash -s \
     "username" "password" "ip address" "iqn" "mountpoint"
```
