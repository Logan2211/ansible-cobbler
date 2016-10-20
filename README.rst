Cobbler Ansible Role
####################

Ansible role to install and configure `Cobbler`_

Default Variables
=================

See ``defaults/main.yml``

Prerequisites
==================

The config_template plugin must be in your ansible plugins path. The plugin
can be obtained at the `OpenStack-Ansible plugins repo`_

Example Playbook
================

.. code-block:: yaml

    - name: Install cobbler
      hosts: cobbler
      user: root
      roles:
        - { role: "cobbler" }

.. _OpenStack-Ansible plugins repo: https://github.com/openstack/openstack-ansible-plugins
.. _Cobbler: http://cobbler.github.io
