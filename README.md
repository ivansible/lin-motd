# ivansible.lin_motd

[![Github Test Status](https://github.com/ivansible/lin-motd/workflows/test/badge.svg?branch=master)](https://github.com/ivansible/lin-motd/actions)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-ivansible.lin__motd-68a.svg?style=flat)](https://galaxy.ansible.com/ivansible/lin_motd/)

This role disables motd banners on ubuntu linux.


## Requirements

None


## Variables

    lin_motd_banner: true


## Tags

- `lin_motd_all` -- that's all


## Dependencies

Imports `hide_secrets` from common role `lin_base`.


## Example Playbook

    - hosts: myhost
      roles:
         - role: ivansible.lin_motd


## License

MIT


## Author Information

Created in 2019-2021 by [IvanSible](https://github.com/ivansible)
