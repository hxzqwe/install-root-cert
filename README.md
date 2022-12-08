# Ansible Role: Install Root CA Certificate

**Import Root CA cert file to `files/ca` directory**

## Example Playbooks

```yaml
- hosts: all
  remote_user: root

  roles:
    - install-root-cert
```
