glance ansible role
===================

[![Build Status](https://travis-ci.org/marklee77/ansible-role-glance.svg?branch=master)](https://travis-ci.org/marklee77/ansible-role-glance)

The purpose of this role is to deploy glance onto Ubuntu. 

Role Variables
--------------

- openstack_mysql_host: 127.0.0.1
- openstack_mysql_port: 3306
- openstack_identity_region: RegionOne

Example Playbook
-------------------------

    - hosts: all
      sudo: True
      roles:
        - glance

License
-------

GPLv2

Author Information
------------------

http://stillwell.me
