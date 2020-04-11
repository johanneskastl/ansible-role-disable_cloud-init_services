![Ansible Lint](https://github.com/johanneskastl/ansible-role-ansible-role-disable_cloud-init_services/workflows/Ansible%20Lint/badge.svg)

ansible-role-disable_cloud-init_services
=========

Disable cloud-init services that are only needed for the initial configuration and might harm later on

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: johanneskastl.disable_cloud-init_services}

License
-------

BSD-3-Clause

Author Information
------------------

I am Johannes Kastl, reachable via kastl@b1-systems.de.
