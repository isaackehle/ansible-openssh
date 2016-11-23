# Ansible: ssh-config-copy

Push or Pull SSH configuration to/from a server

Available on Ansible Galaxy: [pgkehle.ssh-config-copy](https://galaxy.ansible.com/pgkehle/ssh-config-copy)

# Examples

## Pull from a server 

```YAML
- hosts: all
  roles:
    - { role: pgkehle.ssh-config-copy,
        local_path_base: ~/private/certs,
        tags: ["pull"] }
```

## Push from a server 

```YAML
- hosts: all
  roles:
    - { role: pgkehle.ssh-config-copy,
        local_path_base: ~/private/certs,
        tags: ["push"] }
```

## License

MIT

## Author Information

Paul Kehle  
@pgkehle ([twitter](https://twitter.com/pgkehle), [github](https://github.com/pgkehle), [linkedin](https://www.linkedin.com/in/pgkehle))
