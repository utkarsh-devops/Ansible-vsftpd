# Ansible role: vsftpd

This role install latest version of vsftpd, with virtual user management, TLS support and some new configuration options. The mounting task also has been changed from the original role.

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)


# Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yml
- hosts: servers
  roles:
    - ansible-vsftpd
```

## License

MIT

