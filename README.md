golang
======

[![Build Status](https://travis-ci.org/kbrebanov/ansible-golang.svg?branch=master)](https://travis-ci.org/kbrebanov/ansible-golang)

Installs Go language

Requirements
------------

This role requires Ansible 1.9 or higher.

Role Variables
--------------

| Name           | Default | Description              |
|:---------------|:--------|:-------------------------|
| golang_version | 1.6     | Version of Go to install |

Dependencies
------------

None

Example Playbook
----------------

Install Go language using the default version
```
- hosts: all
  roles:
    - { role: kbrebanov.golang }
```

Install Go language specifying a version
```
- hosts: all
  roles:
    - { role: kbrebanov.golang, golang_version: 1.2 }
```

License
-------

BSD

Author Information
------------------

Kevin Brebanov
