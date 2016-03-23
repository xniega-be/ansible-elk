Ansible-ELK
=========
[![Build Status](https://travis-ci.org/bingoarunprasath/ansible-elk.svg?branch=master)](https://travis-ci.org/bingoarunprasath/ansible-elk) [![Ansible Galaxy](https://img.shields.io/badge/galaxy-bingoarunprasath.elk-660198.svg)](https://galaxy.ansible.com/bingoarunprasath/elk/)

Ansible role to install ELK stack in Redhat 7 / CentOS 7 environments

Requirements
------------

CentOS 7 / Redhat 7

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.


Example Playbook
----------------

    - hosts: monitoring
      sudo: yes
      roles:
         - { role: "ansible-elk" }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
