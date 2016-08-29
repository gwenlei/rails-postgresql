Role Name
=========
gwenlei.rails-nginx

Requirements
------------
ubuntu16.04 xenial

Role Variables
--------------
defaults/main.yml

psql_version: 9.4
psql_repo: 'deb http://apt.postgresql.org/pub/repos/apt/ xenial-pgdg main'
psql_url: https://www.postgresql.org/media/keys/ACCC4CF8.asc
dbname: demodb
dbuser: demouser
dbpassword: demopass

Dependencies
------------
none

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: gwenlei.rails-nginx }

License
-------
MIT

Author Information
------------------
onecloud
