set_hostname
============
[![Ansible Lint](https://github.com/oxivanisher/role-set_hostname/actions/workflows/ansible-lint.yml/badge.svg)](https://github.com/oxivanisher/role-set_hostname/actions/workflows/ansible-lint.yml)

This role sets the hostname of the system to the ansible `inventory_hostname_short`.

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------
```yaml
- name: Raspberry Pi
  hosts: rpis
  roles:
    - role: oxivanisher.linux_base.set_hostname
```

License
-------

BSD

Author Information
------------------

This role is part of the [oxivanisher.linux_base](https://galaxy.ansible.com/ui/repo/published/oxivanisher/linux_base/) collection, and the source for that is located on [github](https://github.com/oxivanisher/collection-linux_base).
