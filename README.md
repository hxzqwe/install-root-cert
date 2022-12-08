# Ansible Role: Install Root CA Certificate

Supports the following Operating Systems:

- CentOS 6+
- Ubuntu 14.04+


## Usage

**Import Root CA cert file to `files` directory**

Example Playbooks

```yaml
- hosts: all
  remote_user: root

  roles:
    - install-root-cert
```
