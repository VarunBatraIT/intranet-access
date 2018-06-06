Intranet Access
=========

Intranet Access adds SSH key of yours in all the servers.
Intranet Access adds SSH key of all the servers in your inventory in each other.

Requirements
------------

Ansible 2X

Role Variables
--------------

USERNAME: "developer"

You need a username which is common in every host. 

Dependencies
------------

none

Example Playbook
----------------


    - hosts: servers
      roles:
         - { role: VarunBatraIT.intranet-access, USERNAME: "developer" }

License
-------

MIT

Author Information
------------------

Maintained by Varun Batra [https://varunbatra.com](https://varunbatra.com)
