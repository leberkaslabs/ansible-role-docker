# Ansible Role: docker

[![Ansible Molecule](https://github.com/leberkaslabs/ansible-role-docker/actions/workflows/molecule.yml/badge.svg)](https://github.com/leberkaslabs/ansible-role-docker/actions/workflows/molecule.yml)

Install Docker Engine.

## Prerequisites

- Ensure you have Ansible installed (e.g. `pip3 install ansible`)
- **Development**: Install the pip packages listed in [requirements.txt](requirements.txt)

## Role Variables

The default values for the variables are set in [defaults/main.yml](defaults/main.yml)

```yaml
- hosts: all
  roles:
    - role: leberkaslabs.docker
```

## License

Copyright (c) 2026 Niclas Spreng
