# ansible-snort

Installs and configures [Snort IDS](https://snort.org/)

## Requirements

None

## Role Variables

[defaults/main.yml](defaults/main.yml)

## Dependencies

None

## Example Playbook

```yaml
---
- hosts: all
  become: true
  vars:
  roles:
    - role: ansible-snort
  tasks:
```

## License

MIT

## Author Information

IT-Kombinat

- [@it-kombinat](https://www.twitter.com/it-kombinat)
