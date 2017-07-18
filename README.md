Minecraft ansible role
=========

[![Build Status](https://travis-ci.org/ilbonzo/ansible-minecraft.svg?branch=master)](https://travis-ci.org/ilbonzo/ansible-minecraft)

Install Minecraft server with ansible in debian distribution

Requirements
------------

Debian based system

Role Variables
--------------

There are no mandatory variables.

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

