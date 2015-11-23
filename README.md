panxatony.omd-client
=========

Ansible role used to add new clients to OMD instance.

Requirements
------------

OMD Server must be installed and defined in playbook or defaults/main.yml

Role Variables
--------------

    omd_site - Name of OMD instance
    omd_server: IP or FQDN of OMD instance
    omd_client_folder: Wato Folder which shall be used for client
    omd_clientname: Name of system used in OMD
    omd_client_tags: Host Tags


Dependencies
------------

none.

Example Playbook
----------------

Example of how to use this role:

    - hosts: omd-clients
      roles:
         - { role: panxatony.omd-client, omd-site: cs9lab }

License
-------

BSD

Author Information
------------------

Panxatony
