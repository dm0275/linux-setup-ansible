Role Name
=========

This role sets up a linux workstation.

Requirements
------------

This role is compatible with Ubuntu and Centos.

Role Variables
--------------

The `user` variable has a default value of `vagrant` and should be updated with the desired user account

Dependencies
------------

N/A

Example Usage
----------------

    - hosts: servers
      roles:
         - { role: linux-setup-ansible }

License
-------

BSD
