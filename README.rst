==================
ansible-role-statsd
==================

Ansible role to manage statsd

* License: Apache License, Version 2.0
* Documentation: https://ansible-role-statsd.readthedocs.org
* Source: https://git.openstack.org/cgit/openstack/ansible-role-statsd
* Bugs: https://bugs.launchpad.net/ansible-role-statsd

Description
-----------

Daemon for easy but powerful stats aggregation.

Requirements
------------

See `bindep.txt` for role dependencies.

Packages
~~~~~~~~

Package repository index files should be up to date before using this role, we
do not manage them.

Role Variables
--------------

Dependencies
------------

Example Playbook
----------------

.. code-block:: yaml

    - name: Install statsd
      hosts: statsd
      roles:
        - ansible-role-statsd
