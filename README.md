# Ansible Playbook for allenhair-laptop

This ansible playbook will configure my laptop after reimaging.

## Prerequisites

Both ansible and git must be installed before this playbook can be used:

```console
$ sudo apt install ansible git
```

## Usage

Use the ansible-pull command to clone this playbook and run it:

```console
$ ansible-pull -K -i "allenhair-laptop," -U https://github.com/allenhair/allenhair-laptop.git
```

Alternatively, the playbook can be run from a local checkout by using the
ansible-playbook command:

```console
$ git clone git@github.com:allenhair/allenhair-laptop.git
Cloning into 'allenhair-laptop'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (5/5), done.
remote: Total 72 (delta 1), reused 5 (delta 1), pack-reused 66
Receiving objects: 100% (72/72), 8.59 KiB | 2.86 MiB/s, done.
Resolving deltas: 100% (25/25), done.
$ cd allenhair-laptop
$ ansible-playbook -K -i "allenhair-laptop," local.yml
```

