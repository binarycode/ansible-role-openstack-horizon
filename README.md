Ansible Role: OpenStack Horizon
===============================

This role installs and configures OpenStack Horizon on EL7 system.

Requirements
------------

None.

Role Variables
--------------

Available variables are listed below, along with default values (see `defaults/main.yml`)

    host: controller

Host that runs Horizon.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - binarycode.openstack-horizon

License
-------

BSD

Author Information
------------------

[Igor Sidorov](https://github.com/binarycode)
