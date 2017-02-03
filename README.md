# Ansible Role: telosys for symfony

Install telosys for symfony ready to use package.

## Requirements

In order to exploit this package, we invite you to use the development stack set up.
It allows the transparent management of the various dependencies necessary for the proper functioning of telosys for symfony.

## DevStack

You can use this project associating it with devStack for dev ansible role.

The main project here:

    https://github.com/logorn/dev_stack

*Inside `roles` directory*:

    git clone https://github.com/logorn/ansible-role-telosys-symfony.git telosys-php

Example Playbook

*Inside `devstack.yml`, add this*:

    - hosts: devstack
      roles:
        - role: telosys-php
          tags: telosys-php
    ...

and play now your provision ...

## Goal

The project goal is to automatically deploy the configuration needed for an operational Symfony application by having all the standard packages for setting up a back-end based on elasticsearch, mongodb, mysql.

## Author Information

This role was created in 2017 by Hugues MAILLET, inspired by Ansible for DevOps and the work of many.