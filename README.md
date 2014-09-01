Ansible Role - RockMongo
========================

A RockMongo role to install RockMongo on elao symfony standard vagrant box


Requirements
------------

This role only run on elao symfony standard vagrant box. See https://vagrantcloud.com/elao/symfony-standard-debian


Role Variables
--------------

    elao_rockmongo_host: rockmongo  # RockMongo host


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: elao.rockmongo }


License
-------

MIT


Author Information
------------------

http://www.elao.com/
