# Ansible Role: nnn

![Travis CI](https://travis-ci.org/fesaille/ansible-role-nnn.svg?branch=master)

This role installs [nnn](https://github.com/jarun/nnn) on Debian/Ubuntu Linux system.
```terminal
ansible-galaxy install fesaille.nnn
```

## Requirements



## Role Variables

This role installs the latest tagged version from git, no variable at the moment.


## Dependencies

[geerlingguy.git](https://github.com/geerlingguy/ansible-role-git)


## Example Playbook

    - hosts: servers
      roles:
         - { role: fesaille.nnn }

## Linting

Linting is included in a [`pre-hook`](https://git-scm.com/book/en/v2/Customizing-Git-Git-Hooks) in git

## License

MIT/BSD

