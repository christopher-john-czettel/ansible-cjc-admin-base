cjc-admin-base
==============

Ansible role that installs a few default packages I like having around when working on a Debian/Ubuntu system.

Packages
--------

 * htop
 * tmux
 * vim-nox
 * nmap
 * nload
 * curl
 * nmap
 * git
 * iptraf
 * strace
 * mtr
 * vnstat
 * tcptrack
 * socat
 * apachetop 

 
Installation
============


Add following to your requirements.yml:

```
- src: git+https://github.com/christopher-john-czettel/ansible-cjc-admin-base
  version: "master"
  name: cjc-admin-base
  path : external
```

Then run:

```
ansible-galaxy install -r requirements.yml
```


License
=======

MIT

Author Information
==================

Christopher John CZETTEL (<chris@christopher-czettel.net>)
