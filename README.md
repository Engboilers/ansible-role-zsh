# Ansible Role: Zsh

[![Build Status](https://travis-ci.org/engboilers/ansible-role-zsh.svg?branch=master)](https://travis-ci.org/engboilers/ansible-role-zsh)

Installs zsh and configures it as the default shell.

## Requirements

None.

## Role Variables

None.

## Dependencies

  - [Engboilers.homebrew](https://galaxy.ansible.com/engboilers/homebrew/)

## Example Playbook

    - hosts: localhost
      roles:
        - { role: Engboilers.zsh, zsh_execute: true }

## License

Apache 2.0
