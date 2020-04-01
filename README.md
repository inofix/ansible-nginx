NGINX
=====

Install the NGINX webserver, plain and quick.

State
-----

Unstable.

Installation
------------

    # ansible-galaxy install inofix.nginx

Requirements
------------

* Ansible >2.0
* Python2/3 on target host
* Generic UNIX with FHS
* Sudo

Role Variables
--------------


Dependencies
------------


Example Playbook
----------------

    - hosts: servers
      roles:
         - inofix.nginx

License
-------

GPLv3

Author Information
------------------

* Michael Lustenberger at [inofix.ch](http://www.inofix.ch)

