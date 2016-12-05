[![Build Status](https://travis-ci.org/wtanaka/ansible-role-php52-fpm.svg?branch=master)](https://travis-ci.org/wtanaka/ansible-role-php52-fpm)
[![CircleCI](https://circleci.com/gh/wtanaka/ansible-role-php52-fpm.svg?style=svg)](https://circleci.com/gh/wtanaka/ansible-role-php52-fpm)

wtanaka.php52-fpm
=================

Ansible role to install php52-fpm

Example Playbook
----------------

    - hosts: all
      roles:
         - role: wtanaka.php52-fpm
           php52_fpm_listen: 127.0.0.1:9000

License
-------

GPLv2

Author Information
------------------

http://wtanaka.com/
