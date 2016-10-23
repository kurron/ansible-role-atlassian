Role Name
=========

Installation of tools than any self-respecting [Atlassian](https://www.atlassian.com/) user loves and needs.

Requirements
------------

TODO

Role Variables
--------------

* atlassian_hipchat_install: true

Dependencies
------------

No dependencies.

Example Playbook
----------------

```
- hosts: servers
  roles:
      - { role: kurron.atlassian, atlassian_hipchat_install: true
 }
```

License
-------

This project is licensed under the [Apache License Version 2.0, January 2004](http://www.apache.org/licenses/).

Author Information
------------------

[Author's website](http://jvmguy.com/).
