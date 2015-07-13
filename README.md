## vagrant

[![Build Status](https://travis-ci.org/Oefenweb/ansible-vagrant.svg?branch=master)](https://travis-ci.org/Oefenweb/ansible-vagrant) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-vagrant-blue.svg)](https://galaxy.ansible.com/list#/roles/4366)

Set up [vagrant](https://www.vagrantup.com/) in Debian-like systems.

#### Requirements

None

#### Variables

* `vagrant_version` [default: `1.7.3`]: Version to install

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
    - vagrant
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-vagrant/issues)!
