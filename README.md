# Ansible

[![Build Status](https://drone.osshelp.ru/api/badges/ansible/ansible/status.svg)](https://drone.osshelp.ru/ansible/ansible)

Simple role which install [Ansible](https://github.com/ansible/ansible) and optionally [Mitogen](https://github.com/mitogen-hq/mitogen).

## Usage (example)

Typical installation:

``` yaml
    - role: ansible
      minimal_version: "2.8.1"
      ansible_mitogen_support: true
```

## Available parameters

### Main

Short description here.

| Param | Default | Description |
| -------- | -------- | -------- |
| `ansible_setup` | `full` | Setup mode. See [OSSHelp KB article](https://oss.help/kb4895) |
| `minimal_version` | `2.8.1` | Minimal Ansible version to install |
| `mitogen_version` | `0.2.9` | Mitogen version to install |
| `ansible_mitogen_support` | `false` | Enable mitogen installation |

## FAQ

None, so far.

## Useful links

- [Official documentation for Ansible](https://docs.ansible.com/)
- [Official documentation for Mitogen](https://mitogen.networkgenomics.com/index.html)
- [Ansible role for Molecule](https://github.com/OSSHelp/ansible-molecule)
- [Molecule plugin for Drone CI](https://github.com/OSSHelp/drone-molecule)

## TODO

None, so far.

## License

GPL3

## Author

OSSHelp Team, see <https://oss.help>
