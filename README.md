# Ansible Role to manage users and groups

Tested on:
- CentOS 7
- Debian Jessie
- Debian Stretch
- Ubuntu Xenial
- Ubuntu Bionic

Example code is included in `tests/test.yml`.

The `linux_groups` variable accepts the same parameters as the [group module](https://docs.ansible.com/ansible/latest/modules/group_module.html).

The `linux_users` variable accepts the same parameters as the [user module](https://docs.ansible.com/ansible/latest/modules/user_module.html).
Additionally it also accepts a list of authorized keys using the `ssh_keys` key which accept the same parameters as the [authorized_key module](https://docs.ansible.com/ansible/latest/modules/authorized_key_module.html).
