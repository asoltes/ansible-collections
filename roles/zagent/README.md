Zabbix Agent Installation
=========

ansible role for zabbix agent installation

Requirements
------------
* Zabbix-Server
* Docker
* Ansible 2.11.6

Tested In Linux OS
------------
* Centos 7 
* Centos 8
* Ubuntu 18.04
* Ubuntu 20.04

Role Variables
--------------

* zabbix_server: zabbix-server domain or ip address
* metadataItem: system.sw.os[short]
* zabbix_user: zabbix
* docker_group: docker



Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      gather_facts: True
      roles:
         - zagent

License
-------

BSD

Author Information
------------------

Andrew Soltes
