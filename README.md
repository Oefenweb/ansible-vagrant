## vagrant

[![CI](https://github.com/Oefenweb/ansible-vagrant/workflows/CI/badge.svg)](https://github.com/Oefenweb/ansible-vagrant/actions?query=workflow%3ACI)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-vagrant-blue.svg)](https://galaxy.ansible.com/Oefenweb/vagrant)

Set up [vagrant](https://www.vagrantup.com/) in Debian-like systems.

#### Requirements

* `software-properties-common` (will be installed)
* `dirmngr` (will be installed)
* `apt-transport-https` (will be installed)
* `wget` (will be installed)

#### Variables

None

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
    - oefenweb.vagrant
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-vagrant/issues)!
