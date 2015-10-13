# iscsi-softlayer-ubuntu14
#####Simple script to set up Softlayer iSCSI block storage on Ubuntu 14 machines

### NOTICE
This script is provided without warranty. I needed something to automate the configuration of
several Ubuntu 14 nodes in a cluster of machines hosted on Softlayer. I can't promise that it
will work on your configuration, and I can't imagine it will if your configuration does not
match mine (softlayer, ubuntu 14.04, iscsi block storage also on softlayer).

### HOWEVER
I couldn't find good documentation for this process online, so feel free to use these files as reference!

### USAGE
Step 1:
```
read/understand what this script does before piping into an elevated shell
```
Step 2:
```
curl https://raw.githubusercontent.com/navargas/iscsi-softlayer-ubuntu14/master/run | bash -s \
     "username" "password" "ip address" "iqn" "mountpoint"
```
