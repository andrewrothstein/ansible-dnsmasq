andrewrothstein.dnsmasq
===========================
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-dnsmasq.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-dnsmasq)

A role for installing [dnsmasq](http://www.thekelleys.org.uk/dnsmasq/doc.html) with the operating system package manager

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.dnsmasq
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
