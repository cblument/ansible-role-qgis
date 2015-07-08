qgis
=========

Installs latest qgis from http://www.qgis.org for Ubuntu trusty

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

None
Example Playbook
----------------

    - hosts: localhost
      connection: local
      sudo: true
      gather_facts: false

      roles:
         - qgis

```
ansible-playbook --ask-sudo-pass play.yml
```

License
-------

MIT

Author Information
------------------

Chris Blumentritt

