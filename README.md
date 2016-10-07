wrboyce.dotfiles-assh
=====================

[![Build Status](https://travis-ci.org/wrboyce/ansible-dotfiles-assh.svg)](https://travis-ci.org/wrboyce/ansible-dotfiles-assh)

Configure ssh via [assh](https://github.com/moul/advanced-ssh-config).

Role Variables
--------------

This role exposes three variables which map verbatim to the assh configuration variables:
`assh_defaults`, `assh_templates`, and `assh_hosts`. See `defaults/main.yml` for example usage.


Example Playbook
----------------

    - hosts: workstations
      roles:
         - wrboyce.dotfiles-assh

License
-------

Apache 2.0