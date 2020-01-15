## DRBD + Pacemaker + PostgreSQL -> Ansible

### How to use

* edit hosts.yml
* edit group_vars/all.yml
* $ ansible-playbook cluster.yml -i hosts.yml

### Special Thanks

* https://github.com/yteraoka/postgresql10-pacemaker
* https://github.com/hnakamur/postgresql-pacemaker-example-playbook
