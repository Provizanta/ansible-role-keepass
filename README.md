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

    - hosts: localhost
      roles:
        - role: keepass
          vars:
            plugins:
              - keeagent
              - status-notifier

License
-------

MIT

Author Information
------------------

Tibor Csóka
