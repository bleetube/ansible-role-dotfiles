# Ansible Role: dotfiles

This role sets up my dotfiles.

Tested on:

* Archlinux
* Debian 10, 11, 12
* Ubuntu 20.04, 22.04
* !RedHat 7.9

## Requirements

None.

## Example Playbook

```yaml
- hosts: all
  become: true
  roles:
    - bleetube.dotfiles
```

## Resources

* [GNU Readline Init File Syntax](http://www.gnu.org/software/bash/manual/html_node/Readline-Init-File-Syntax.html)

## Troubleshooting

```vim
:scriptnames
:set runtimepath?
:version
```

Also `vim -V`