crystalspace
============

[![Build Status](https://travis-ci.org/nabilbendafi/ansible-role-crystalspace.png?branch=master)](https://travis-ci.org/nabilbendafi/ansible-role-crystalspace)

This role installs and configures the open-source 3D SDK [crystalspace](http://crystalspace3d.org/).

Installation
------------

```
$ ansible-galaxy install nabilbendafi.ansible-role-crystalspace 
```

```
# crystalspace.yml
- hosts: localhost
  roles:
    - nabilbendafi.crystalspace
```

```
$ ansible-playbook crystalspace.yml
```

Dependencies
------------

None

License
-------

[MIT](LICENSE.txt)

Author Information
------------------

[Nabil Bendafi](https://github.com/nabilbendafi)
