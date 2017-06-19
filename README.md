NGINX & Certbot base installation
=========

A role to deploy a base installation of NGINX and certbot (letsencrypt).
To actually install sites, the roles nginx_vhost and certbot_domain are needed.

Requirements
------------

A working operating system. Debian or CentOS.

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
         - role: ZeusWPI.nginx_certbot_base
           tags: nginx
```
But you probably want to add this as a dependency, or use the `ZeusWPI.nginx_vhost` and `ZeusWPI.certbot_domain` roles which have this role as a dependency.

License
-------

GNU General Public License v3.0

Author Information
------------------

For questions, clarifications or other chitchat, contact me at [maertensrien@gmail.com](mailto:maertensrien@gmail.com).

