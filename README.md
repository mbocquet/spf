# spf

An Ansible role to install and configure SPF (Sender Policy
Framework) for Postfix.

## Requirements

A running postfix instance.

## Role Variables

Many. See defaults/main.yml.

## Dependencies

You should run a Postfix instance on the host to use this role.

## Install this role as submodule of an existing GIT repository

`git submodule add https://github.com/mbocquet/spf.git roles/spf`

## Example Playbook

    - hosts: servers
      roles:
        - spf


    - hosts: servers
      roles:
        - { role: spf, x: 42 }

if any variables comes in the future for this role.

## License

GPLv3

## Author Information

<a href="http://www.sekoya.org" target="new">http://www.sekoya.org</a>
