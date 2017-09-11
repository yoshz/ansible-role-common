yoshzz.common
=============

An Ansible role for basic common system configuration:

- Install latest system packages
- Enable password-less sudo for admin group
- Restrict SSH and enable ufw
- Install and configure swapfile (very useful for small cloud instances) 

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

License
-------

MIT

Author Information
------------------

Yosh de Vos <yosh@elzorro.nl>
