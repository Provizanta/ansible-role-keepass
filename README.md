Keepass
=========

Keepass keychain for password and key management.

Requirements
------------

None

Role Variables
--------------

A list of plugins that should be installed.

    plugins:
      - keeagent
      - rpc
      ...

Dependencies
------------

None

Example Playbook
----------------
Only plugins can be additionally specified in a variable passed to 'keepass' role.

    - hosts: localhost
      roles:
        - keepass
          vars:
            plugins:
              - keeagent
              - rpc
              - status-notifier

License
-------

MIT

Author Information
------------------

Tibor Csoka
