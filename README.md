Ansible role: Keepass
=========

![Build & Deploy](https://github.com/Provizanta/ansible-role-keepass/workflows/molecule/badge.svg?branch=master)

Keepass keychain for password and key management.

Requirements
------------

None

Role Variables
--------------

These variables are defined in [defaults/main.yml](./defaults/main.yml):

    keepass_plugins: []     # list of plugins to be installed

Dependencies
------------

None

Example Playbook
----------------

    - name: Converge
      hosts: all
      roles:
        - role: keepass
          vars:
            keepass_plugins:
              - keepass2-plugin-tray-icon

License
-------

MIT

Author Information
------------------

Tibor Csóka
