# Ansible: ssh-config-copy

Push or Pull SSH configuration to/from a server

Available on Ansible Galaxy: [pgkehle.ssh-config-copy](https://galaxy.ansible.com/pgkehle/ssh-config-copy)

# Examples

## Pull from a server 

```YAML
 - hosts: all
   roles:
     - pgkehle.ssh-config-copy
       copy_action: pull
```

## Push from a server 

```YAML
 - hosts: all
   roles:
     - pgkehle.ssh-config-copy
       copy_action: push
```

## License

MIT

## Author Information

Paul Kehle  
@pgkehle ([twitter](https://twitter.com/pgkehle), [github](https://github.com/pgkehle), [linkedin](https://www.linkedin.com/in/pgkehle))
