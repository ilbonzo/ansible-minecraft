Minecraft ansible role
=========

[![Ansible Galaxy](https://img.shields.io/badge/role-ilbonzo.minecraft-blue.svg)](https://galaxy.ansible.com/ilbonzo/minecraft)
[![Build Status](https://travis-ci.org/ilbonzo/ansible-minecraft.svg?branch=master)](https://travis-ci.org/ilbonzo/ansible-minecraft)

Install Minecraft server with ansible in debian distribution

Requirements
------------

Debian based system

Role Variables
--------------

There are no mandatory variables.  Minecraft 1.10.2 will be installed by default.  You can specify a custom version:

```yaml
minecraft_server_version: 1.14.3
```

Dependencies
------------

There are no dependencies

Example Playbook
----------------

    - hosts: all
      roles:
      - role: minecraft
        become: yes

License
-------

Apache license
