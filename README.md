# Ansible Role: httpd

An Ansible role to install and configure Apache HTTP Server (httpd) on Linux servers.

## Requirements

No special requirements.

## Role Variables

Available variables are listed below, along with their default values (see `defaults/main.yml`):

```yaml
httpd_port: 80
httpd_document_root: /var/www/html

Dependencies
------------

None.

Example Playbook
----------------

- hosts: servers
  roles:
    - role: prosenjitdey2143.httpd


License
-------

MIT

Author Information
------------------

This role was created in 2024 by Prosenjit Dey. You can find more about me at LinkedIn.
