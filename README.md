# docker-php-apache-oracle12

PHP 7.4 + Apache + Oracle Client V.11/12  
PHP 8.3 + Apache + Oracle Client V.12

# info ver
  
root@10088d27e1d5:/var/www/html# apache2 -v  
Server version: Apache/2.4.54 (Debian)  
Server built:   2022-06-09T04:26:43  
  
root@10088d27e1d5:/var/www/html# php -v  
PHP 7.4.33 (cli) (built: Nov 15 2022 06:03:30) ( NTS )  
Copyright (c) The PHP Group  
Zend Engine v3.4.0, Copyright (c) Zend Technologies  
  
root@10088d27e1d5:/var/www/html# sqlplus -v  
SQL*Plus: Release 12.2.0.1.0 Production  
  
root@10088d27e1d5:/var/www/html# php -i | grep oci  
/usr/local/etc/php/conf.d/php-oci8.ini  
oci8  
oci8.connection_class => no value => no value  
oci8.default_prefetch => 100 => 100  
oci8.events => Off => Off  
oci8.max_persistent => -1 => -1  
oci8.old_oci_close_semantics => Off => Off  
oci8.persistent_timeout => -1 => -1  
oci8.ping_interval => 60 => 60  
oci8.privileged_connect => Off => Off  
oci8.statement_cache_size => 20 => 20  

# credit
base on and modify from https://github.com/adrianharabula/php-oci8
