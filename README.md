# Ansible Playbook for allenhair-laptop

This ansible playbook will configure my laptop after reimaging.

## Prerequisites

Both ansible and git must be installed before this playbook can be used:

```shell
sudo apt install ansible git
```

## Usage

Use the ansible-pull command to clone this playbook and run it:

```shell
ansible-pull -K -i "allenhair-laptop," -U https://github.com/allenhair/allenhair-laptop.git
```

