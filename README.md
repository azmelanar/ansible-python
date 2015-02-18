Python
======

[![Build Status](https://api.travis-ci.org/azmelanar/ansible-python.png)](https://travis-ci.org/azmelanar/ansible-python) [![Ansible Galaxy](https://img.shields.io/badge/ansible--galaxy-azmelanar.python-blue.svg?style=flat)](https://galaxy.ansible.com/list#/roles/2616)

Role for install and manage python.

Requirements
------------

Tested with Ansible 1.8.2

Role Variables
--------------

None

Dependencies
------------

Only one dependency required for install epel repository on RHEL systems:

    azmelanar.epel

Example Playbook
----------------

Example of usage:

    - hosts: servers
      roles:
         - { role: azmelanar.python }

License
-------

MIT

Feedback, improvements, bugs
----------------------------

Please use [issues](https://github.com/azmelanar/ansible-python/issues).
