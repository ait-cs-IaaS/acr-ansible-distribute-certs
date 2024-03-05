# Ansible-Role: acr-ansible-distribute-certs

AIT-CyberRange: Distributes previously generated certs and keys. 


## Requirements

- Debian or Ubuntu 

## Role Variables

```yaml
# root path of the site cert files
cert_src_path: ""
```

## Example Playbook

```yaml
- hosts: all
  roles:
    - acr-ansible-distribute-certs
      vars:
        cert_src_path: "/tmp/data/certs/hostname/"
```

## License

GPL-3.0

## Author

- Lenhard Reuter