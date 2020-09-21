# mysql

[![Build Status](https://travis-ci.com/leafnode/ansible-role-mysql.svg?branch=master)](https://travis-ci.com/leafnode/ansible-role-leafnode)

Ansible role for mysql

This role was prepared and tested for Ubuntu 16.04.

# Installation

`$ ansible-galaxy install leafnode.mysql`

# Default settings

```

mysql_databases: []
mysql_users: []
mysql_root_db_pass: ''
mysql_port: 3306
mysql_bind_addresses: ['127.0.0.1']
mysql_max_connections: 150
mysql_tmp_table_size: 32M
mysql_max_heap_table_size: 32M
mysql_innodb_buffer_pool_size: 16M
mysql_innodb_buffer_pool_instances: 1
mysql_innodb_additional_mem_pool_size: 2M
mysql_table_open_cache: 400
mysql_version: 5.7

```
