
Deploy Collectd Using Ansible
=======================

This role will deploy collectd using Ansible


Requirements
------------

You must have Ansible 2.0 installed.

You need a Slack server

Ideally CentOS 7

Examples
--------

To set deloy collect on a host:

```
ansible-playbook collectd.yml -e hosts=host --sudo -K
