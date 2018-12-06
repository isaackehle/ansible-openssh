# Ansible Role - openssh

Push or Pull OpenSSH configuration to/from a server

Available on Ansible Galaxy: [pgkehle.openssh](https://galaxy.ansible.com/pgkehle/openssh)

# Examples

## Pull from a server 

```YAML
- hosts: all
  roles:
    - { role: pgkehle.openssh,
        local_path_base: ~/private/certs,
        tags: ["pull"] }
```

## Push from a server 

```YAML
- hosts: all
  roles:
    - { role: pgkehle.openssh,
        local_path_base: ~/private/certs,
        tags: ["push"] }
```

## License

MIT

## Author Information

Paul Kehle  
@pgkehle ([twitter](https://twitter.com/pgkehle), [github](https://github.com/pgkehle), [linkedin](https://www.linkedin.com/in/pgkehle))

