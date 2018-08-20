Role Name
=========

ONMP (OpenBSD Nginx MariaDB PHP) installer using ansible

Requirements
------------

None

Role Variables
--------------

```

new_root_password: "" (for new root password)

```

Dependencies
------------

MySQL-python module

Example Playbook
----------------

```

- name: Start ONMP
  gather_facts: True

  vars:
    - new_root_password: "your new root password for mariadb"

  roles:
    - { role: ansible-onmp }

```

License
-------

GPLv3

Author Information
------------------

This role was created at 2018 by elasyaf
