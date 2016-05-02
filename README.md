Ansible-ELK
=========
[![Build Status](https://travis-ci.org/bingoarunprasath/ansible-elk.svg?branch=master)](https://travis-ci.org/bingoarunprasath/ansible-elk) [![Ansible Galaxy](https://img.shields.io/badge/galaxy-bingoarunprasath.elk-660198.svg)](https://galaxy.ansible.com/bingoarunprasath/elk/)

Ansible role to install ELK stack in Redhat 7 / CentOS 7 environments

Requirements
------------

CentOS 7 / Redhat 7

Role Variables
--------------

Package version can be modified in defaults/main.yml
In the same file, username and password can be changed. 


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
