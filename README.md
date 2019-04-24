Debian-Pure-FTPd
===============

A secure FTP daemon

Requirements
------------

This role requires a debian compliant system such as ubuntu.

Role Variables
--------------

pureftpd:
  version: 1.0.49

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: cowops.debian-pureftpd, pureftpd.version: 1.0.49 }

Tasks
-----

  - Install [Pure-FTPd](https://www.pureftpd.org/)

License
-------

BSD
