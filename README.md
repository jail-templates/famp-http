# Meta package for all templates
Bastille meta-template to install the Apache HTTP server, MariaDB and PHP (FAMP stack).

* https://github.com/jail-templates/apache-http
* https://github.com/jail-templates/php
* https://github.com/jail-templates/mariadb

## Bootstrap
```
bastille bootstrap https://github.com/jail-templates/famp-http
```

## Apply template
```
bastille template $JAIL jail-templates/famp-http
```
