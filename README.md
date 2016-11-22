php-fpm
=======


What is does this role do?
--------------------------

This role installs and configured php-fpm for drop in operation with a *.d directory that other sites may drop items into.


Meta
----

Files Managed:
  * /etc/php/php-fpm.conf
  * /etc/php/php-fpm.d/www.conf
  * /etc/php/conf.d/
  * /var/service/php-fpm

Defaults Provided:
  * None

Variables Required:
  * None

Optional Variables:
  * None

Files Required:
  * None

Optional Files:
  * None

Conflicting Roles:
  * None

Depends On:
  * None
