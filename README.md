Role Name
==========

dns_setup

Requirements
------------

You will need to set/define all the variables in the defaults variable file in 'defaults/main.yml'. Use the pre-compiled on as a guide line.

Role Variables
--------------

If you need/want to add additional variables you can.

Dependencies
------------

The target host needs to have already been installed with base OS Centos7.

Example Playbook
----------------

  - name: Init
    hosts: dns1.lubs.local
    become: true

    roles:
      - dns_setup

License
-------

BSD

Author Information
------------------

Name: Micka Kadima Luboya
Blog: cybersecmickey.blogspot.com
