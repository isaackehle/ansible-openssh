# Ansible Role - openssh

Push or Pull OpenSSH configuration to/from a server

Available on Ansible Galaxy: [isaackehle.openssh](https://galaxy.ansible.com/isaackehle/openssh)

## Examples

### Pull from a server

```yaml
- hosts: all
  roles:
    - { role: isaackehle.openssh, local_path_base: ~/private/certs, tags: ["pull"] }
```

### Push from a server

```yaml
- hosts: all
  roles:
    - { role: isaackehle.openssh, local_path_base: ~/private/certs, tags: ["push"] }
```

## Linting

```bash
yamllint -c yamllint.yaml .
ansible-lint .
```

## License

MIT

## Author Information

Isaac Kehle
@isaackehle ([twitter](https://twitter.com/isaackehle), [github](https://github.com/isaackehle), [linkedin](https://www.linkedin.com/in/isaackehle))
