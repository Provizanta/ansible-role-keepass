Keepass
=========

[![Build Status](https://travis-ci.com/Provizanta/ansible-role-keepass.svg?branch=master)](https://travis-ci.com/Provizanta/ansible-role-keepass)

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
