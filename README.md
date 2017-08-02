# Ansible Role: resilio-sync

[![Build Status](https://travis-ci.org/sparanoid/ansible-resilio-sync.svg)](https://travis-ci.org/sparanoid/ansible-resilio-sync)

Install [resilio-sync](https://www.resilio.com/) via Ansible.

## Requirements

This role requires Ansible 1.6 or higher and platform requirements are listed in the metadata file.

## Dependencies

None

## Example Playbooks

Install resilio-sync:

```yaml
- hosts: servers
  roles:
    - { role: sparanoid.resilio-sync }
```

## License

MIT

## Author Information

**Tunghsiao Liu**

- Twitter: @[tunghsiao](http://twitter.com/tunghsiao)
- GitHub: @[sparanoid](http://github.com/sparanoid)
