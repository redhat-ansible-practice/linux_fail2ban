Linux_fail2ban
=========

This role installs fail2ban, copies over a jail.local that is used to protect ssh and starts the service.

Requirements
------------

N/A

Role Variables
--------------

N/A

No variables since all the default module options are what is exactly needed for this. If we need to protect more services then we can add to the current templated jail file or create one for each service.

Dependencies
------------

Example Playbook
----------------

    - hosts: servers
      roles:
         - linux_fail2ban

License
-------

GPLv2

Author Information
------------------

jlozadad@redhat.com


