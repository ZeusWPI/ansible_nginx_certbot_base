Role Name
=========

A role to install NGINX.

Requirements
------------

A working operating system.

Role Variables
--------------

Check out `defaults/main.yml`, I try to document each variable there.

Dependencies
------------

None.

Example Playbook
----------------

This example will install this role:

```
    - hosts: servers
      roles:
         - role: R13N.nginx
           tags: nginx_base
```
But you probably want to add this as a dependency, or use the `nginx_vhost` role.

License
-------

GNU General Public License v3.0

Author Information
------------------

For questions, clarifications or other chitchat, contact me at [maertensrien@gmail.com](mailto:maertensrien@gmail.com).

