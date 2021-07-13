Ansible Role: phpMyAdmin(src)
================================================================================
Install and configure phpMyAdmin

- Install phpMyAdmin from the source archive
- Configure phpMyAdmin-root/config.inc

Requirements
--------------------------------------------------------------------------------

Role Variables
--------------------------------------------------------------------------------
The following variables are defined in defaults/main.yml file.

```yaml
phpmyadmin:
  destination: "/var/www/html"
  ...
```

Dependencies
--------------------------------------------------------------------------------
None

Example Playbook
--------------------------------------------------------------------------------
```yaml
- hosts: servers
  roles:
     - { role: azumakuniyuki.ar-phpmyadmin-src }
```

License
--------------------------------------------------------------------------------
BSD

Author Information
--------------------------------------------------------------------------------
[azumakuniyuki](https://nyaan.jp)

