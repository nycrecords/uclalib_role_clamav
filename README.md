UCLALib Ansible Role: ClamAV
=========

Installs the ClamAV Antivirus Software and the ClamAV daemon

Requirements
------------

Only supports RHEL-family servers at this time.

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

```
---
    - name: uclalib_clamav_app.yml
      sudo: true
      hosts: servers

    roles:
      - { role: uclalib_role_clamav }

```

License
-------

BSD

