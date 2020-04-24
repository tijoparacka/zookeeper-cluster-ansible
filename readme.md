# Zookeeper Cluster Setup Using Ansible
It will install Zookeeper cluster on 3 nodes for demo.

## Notes
```
It will install openjdk 8 .
```


## TO RUN

* **STEP-1**
```
cd playbooks
```

* **STEP-2**
```
ansible-playbook -i hosts/cluster-hosts.ini -u <user eg ec2-user > --private-key <key path eg: ~/Documents/ec2.key> cluster-setup.yml
```
# Supported/Tested OS
* CentOS / Amazon Linux
