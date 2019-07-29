Apache
=========

Installs and configure Apache

Requirements
------------

Ansible 2.5+
Python

Role Variables
--------------

Set the Apache port
```
apache_port: 8080
```

Example Playbook
----------------

```
- hosts: webserver
  roles:
    - apache
```

Author Information
------------------

- Name: Andrew Kuttor

