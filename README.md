CTA Archive Role
=========


Role Variables
--------------

- `docker_bridge_ip_cidr` (optional): IP to be assigned to the docker bridge. Using standard CIDR notation, e.g. 192.168.1.5/24

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: indigo-dc.cta-archive }

License
-------

Apache Licence v2 [1]

[1] http://www.apache.org/licenses/LICENSE-2.0
