# docker-php-apache-oracle12

PHP 7.4 + Apache + Oracle Client V.11/12  
PHP 8.4 + Apache + Oracle Client V.11/12

# info ver
root@php-oci8:/var/www/html# apache2 -v  
Server version: Apache/2.4.65 (Debian)  
Server built:   2025-07-29T17:52:31  
##
root@php-oci8:/var/www/html# php --ri oci8  
  
oci8  
  
OCI8 Support => enabled  
OCI8 DTrace Support => disabled  
OCI8 Version => 3.4.0  
Oracle Run-time Client Library Version => 12.2.0.1.0  
Oracle Compile-time Instant Client Version => 12.2  
  
Directive => Local Value => Master Value  
oci8.max_persistent => -1 => -1  
oci8.persistent_timeout => -1 => -1  
oci8.ping_interval => 60 => 60  
oci8.privileged_connect => Off => Off  
oci8.statement_cache_size => 20 => 20  
oci8.default_prefetch => 100 => 100  
oci8.old_oci_close_semantics => Off => Off  
oci8.connection_class => no value => no value  
oci8.events => Off => Off  
oci8.prefetch_lob_size => 0 => 0  
  
Statistics =>  
Active Persistent Connections => 0  
Active Connections => 0  
##
root@php-oci8:/var/www/html# php -v  
PHP 8.4.12 (cli) (built: Aug 28 2025 18:16:22) (NTS)  
Copyright (c) The PHP Group  
Built by https://github.com/docker-library/php  
Zend Engine v4.4.12, Copyright (c) Zend Technologies  
    with Zend OPcache v8.4.12, Copyright (c), by Zend Technologies  
##
root@php-oci8:/var/www/html# sqlplus -v  
  
SQL*Plus: Release 12.2.0.1.0 Production  
# credit
base on and modify from https://github.com/adrianharabula/php-oci8
