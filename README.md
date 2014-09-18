[![Build Status](https://travis-ci.org/Arkilog/mysql.svg)](https://travis-ci.org/Arkilog/mysql)

Arkilog Ansible provisionner for MySQL 
========

Arkilog Ansible provisionner for MySQL.

Requirements
------------

An ubuntu box.

Role Variables
--------------

The are the variables and their default definition :

```YAML
arkilog_mysql_version: '5.5'
arkilog_mysql_user: 'user'
arkilog_mysql_pwd: 's333cret'
arkilog_mysql_login_user: 'root'
arkilog_mysql_login_pwd: ''
arkilog_mysql_privil: '*.*:ALL'
arkilog_mysql_database_list:
  - '{{ arkilog_mysql_user }}dev'
  - '{{ arkilog_mysql_user }}test'
```

Dependencies
------------

None

License
-------

BSD

Author Information
------------------

http://www.arkilog.ma/contact
