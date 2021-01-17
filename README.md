# Ansible Playbook for allenhair-laptop

This ansible playbook will configure my laptop after reimaging.

## Prerequisites

Both ansible and git must be installed before this playbook can be used:

    sudo apt install ansible git

## Installing

Use the ansible-pull command to clone this playbook and run it:

    ansible-pull -K -i "allenhair-laptop," -U https://github.com/allenhair/allenhair-laptop.git

