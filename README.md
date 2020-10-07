cb-baseline-arole
=========

Ansible role to configure base dependencies for laptop

Requirements
------------

This role should be run as the user you intend to setup.  The `--ask-become-pass` ansible option should be invoked for any tasks that require escalated privileges

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

    ansible-playbook -i localhost, --ask-become-pass playbook.yml

    - hosts: localhost
      connection: local
      roles:
         - cb-baseline

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
