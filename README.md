# Ansible Role: Swap

[![Build Status](https://travis-ci.org/tschifftner/ansible-role-swap.svg)](https://travis-ci.org/tschifftner/ansible-role-swap)

Add swap space on Debian/Ubuntu linux servers.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

```
swap_file: '/root/swapfile'
swap_space: '2G'
```


## Dependencies

None.

## Example Playbook

    - hosts: server
      roles:
        - { role: tschifftner.swap }

## Supported OS

Ansible          | Debian Jessie    | Ubuntu 14.04    | Ubuntu 12.04
:--------------: | :--------------: | :-------------: | :-------------: 
2.1              | Yes              | Yes             | Yes

## License

[MIT License](http://choosealicense.com/licenses/mit/)

## Author Information

 - [Tobias Schifftner](https://twitter.com/tschifftner), [ambimax® GmbH](https://www.ambimax.de)