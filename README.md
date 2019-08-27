centos7-basic-config
=========

Installs libraries required by Alfresco as per the [documentation](https://docs.alfresco.com/5.2/concepts/install-lolibfiles.html).

There are some additional tools that are installed for troubleshooting.

Requirements
------------

Currently only working on Centos 7.

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: sirreeall.centos7-basic-config }

License
-------

Free
