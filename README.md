Role Name
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

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

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

BSD

Author Information
------------------

Chris Blumentritt

