[![Build Status](https://travis-ci.org/brucellino/ansible-grid-security.svg?branch=master)](https://travis-ci.org/brucellino/ansible-grid-security)

Grid Security
=========

A role to set up the grid security profile on relevant nodes.

Requirements
------------

none

Role Variables
--------------

Default VOs are stored in `defaults`. Add yours in `vars`

Dependencies
------------
none

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: worker-nodes,uis
      roles:
         - { role: EGI-Foundation.grid-security, VOS: dteam }

License
-------

Apache-2.0

Author Information
------------------

Pablo Orviz, Bruce Becker
