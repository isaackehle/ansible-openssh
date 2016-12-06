# Ansible: ssh-keys

Push or Pull SSH configuration to/from a server

Available on Ansible Galaxy: [pgkehle.ssh-keys](https://galaxy.ansible.com/pgkehle/ssh-keys)

# Examples

## Pull from a server 

```YAML
- hosts: all
  roles:
    - { role: pgkehle.ssh-keys,
        local_path_base: ~/private/certs,
        tags: ["pull"] }
```

## Push from a server 

```YAML
- hosts: all
  roles:
    - { role: pgkehle.ssh-keys,
        local_path_base: ~/private/certs,
        tags: ["push"] }
```

## License

MIT

## Author Information

Paul Kehle  
@pgkehle ([twitter](https://twitter.com/pgkehle), [github](https://github.com/pgkehle), [linkedin](https://www.linkedin.com/in/pgkehle))
