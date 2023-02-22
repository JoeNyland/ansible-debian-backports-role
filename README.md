joenyland.debian_backports
=========================

[![CI](https://github.com/JoeNyland/ansible-debian-backports-role/actions/workflows/ci.yml/badge.svg)](https://github.com/JoeNyland/ansible-debian-backports-role/actions/workflows/ci.yml)

Installs [Debian backports repo](https://backports.debian.org/).

Requirements
------------

None.

Role Variables
--------------


### `debian_backports_additional_components`

Allows additional 'components' to be selected. E.g. `contrib`.

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- hosts: server
  roles:
    - joenyland.debian_backports
```

License
-------

MIT

Author Information
------------------

⌨️ with ❤️ by [Joe Nyland](https://joe.nyland.io)
