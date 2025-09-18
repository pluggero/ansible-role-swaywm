# Ansible Role: Sway Window Manager

[![CI](https://github.com/pluggero/ansible-role-swaywm/actions/workflows/ci.yml/badge.svg)](https://github.com/pluggero/ansible-role-swaywm/actions/workflows/ci.yml) [![Ansible Galaxy downloads](https://img.shields.io/ansible/role/d/pluggero/swaywm?label=Galaxy%20downloads&logo=ansible&color=%23096598)](https://galaxy.ansible.com/ui/standalone/roles/pluggero/swaywm)

An Ansible Role that installs a basic configuration of sway Window Manger.

## Requirements

Requires a compatible font; Recommended role: `pluggero.nerdfonts`.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

## Dependencies

None.

## Example Playbook

```yaml
- hosts: all
  roles:
    - pluggero.swaywm
```

## License

MIT / BSD

## Author Information

This role was created in 2025 by Robin Plugge.
