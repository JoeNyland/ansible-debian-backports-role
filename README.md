joenyland.debian_backports
=========================

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
# requirements.yml
roles:
  - name: joenyland.debian_backports
    src: https://github.com/JoeNyland/ansible-debian-backports-role
```

```yaml
# Playbook
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
