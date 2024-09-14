ansible-role-step-ca
=========

An Ansible role that deploys a two-tier PKI setup with step-ca in a containerised fashion.
Be advised - this role has been cobbled together due to an intense need in a limited time, so things might break. A lot. There's no automated testing yet, most of my testing has been manual so far. 
Works on openSUSE MicroOS. Did not test on other distros.

Requirements
------------

Working DNS records, a Linux server.

Role Variables
--------------

Most of the variables are self-explanatory in the defaults/main.yml file.

Dependencies
------------

None.


License
-------

MIT
