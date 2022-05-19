Juniper Static Route Configuration
=========

This role will configure basic static routes for JUNOS devices.

Requirements
------------
ncclient


Role Variables
--------------
static_routes:
* route: ip route, string
* next_hop: route next hop, string

Dependencies
------------


Example Playbook
----------------

    - hosts: vmx1
      roles:
         - { role: junos_static_routes }

License
-------

BSD

Author Information
------------------

Marc Colburn
