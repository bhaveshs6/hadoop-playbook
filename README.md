# hadoop-playbook
Ansible playbook to create and launch a hadoop cluster!

-----------
hadoop.yml:
-----------
This is a playbook that has three plays
- The first is to install jdk and hadoop in all hosts.
- The second is to configure, format, start the namenode and allow ports.
- The third is to configure and start the datanode.

------------
ansible.cfg:
------------
This is the config file that tells ansible where the inventory is.

---------
inventory
---------
This is the inventory that contains information about all hosts.
