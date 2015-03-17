Role Name
=========

Deploys Varnish 4 (or 3).

Requirements
------------

None.

Role Variables
--------------

Path to configuration file template

    varnish_config_file: files/varnish/config.j2

Dependencies
------------

None

Example Playbook
----------------

    - hosts: varnishes
      roles:
         - { role: mnn.varnish }

License
-------

GPLv3

Author Information
------------------

Written by Justin Caratzas <jcaratzas@mnn.com> for Mother Nature Network.
