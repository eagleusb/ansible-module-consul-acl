# ansible-module.consul

Ansible collection to distribute Consul module(s).

- `consul_acl`: Consul tokens, roles and policies management with the newest API (Consul >= 1.4)

![ansible-version](https://img.shields.io/badge/ansible-v2.9+-green.svg)
![last-commit](https://img.shields.io/github/last-commit/eagleusb/ansible-module.consul)
![license](https://img.shields.io/github/license/eagleusb/ansible-module.consul)

## Quickstart

- collection installation

```bash
ansible-galaxy collection install eagleusb.consul
```

- playbook usage

```yml
- hosts: all
  collections:
    - eagleusb.consul
  roles:
    - role: ansible-skeleton
```

- role usage

```yml
# role/meta/main.yml
collections:
  - eagleusb.consul
```
