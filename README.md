Role Name
=========

Flashback Oracle database to restore point and reset flashback.

Requirements
------------

Ensure that `/etc/profile.d/oracle.sh` is present and is setting all variables correctly and sqlplus command is present in $PATH

Role Variables
--------------

- restore_point_name: Name of target restore point


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: embedit.oracle-tools-flashback, restore_point_name: some_restore_point }

License
-------

MIT

Author Information
------------------

- Mario Vejlupek
