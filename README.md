# Attention:
In Mariadb 10.1 Galera is in core package and this means i have to rewrite some functions for now this role is useless 

# ansible-role-mariadb-galera
Ansible role to install MariaDB and Galera Cluster



```
---
- hosts: servers
  remote_user: root
  roles:
    - ansible-role-mariadb-galera
```




###To do:
 - Update Documentation
 - Database creation
 - user creation
 - secure-installation
