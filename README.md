spk83.kill-supervisor-eventlistener
===================================
[![Build Status](https://travis-ci.org/spk83/ansible-kill-supervisor-eventlistener.svg?branch=master)](https://travis-ci.org/spk83/ansible-kill-supervisor-eventlistener)

supervisord-eventlistener configuration to kill supervisor based on https://blog.zhaw.ch/icclab/process-management-in-docker-containers/ 

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
    - spk83.kill-supervisor-eventlistener
```

License
-------

MIT

Author Information
------------------

Vishal Shah <vishal.shah@nyu.edu>
