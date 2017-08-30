# docker-alpine-LAMPS
#### LAMPS (Linux-Apache-Mariadb-Php-Subversion) in a group of docker Alpine Linux images

____

The docker-alpine-LAMPS repository contains a group of shell scripts designed to install a "latest" version of a LAMPS system (Linux-Apache-MariaDB-Php-Subversion) system.  The following docker-based Alpine Linux images will be installed on a Linux host:

  - Apache 2.2 Web Server
    + from nimmis/alpine-apache-php7 (https://hub.docker.com/r/nimmis/apache-php7/)  
or
    + from nimmis/alpine-apache-php5 (https://hub.docker.com/r/nimmis/apache-php5/)  
or both
  
  - MariaDB Database Server (a MySql spin)
    + from nimmis/alpine-mariadb (https://hub.docker.com/r/nimmis/alpine-mariadb/)
    
  - PHP 7 or PHP 5 or both
    + from nimmis/alpine-apache-php7 (https://hub.docker.com/r/nimmis/apache-php7/)
    + from nimmis/alpine-apache-php5 (https://hub.docker.com/r/nimmis/apache-php5/)

  - Subversion Repository Server using Apache2.2 + WebDAV + SVN_DAV-SVN
    + from earthwalksoftware/alpine-svn (https://hub.docker.com/r/earthwalksoftware/alpine-svn/)

  - phpMyAdmin
    + from phpmyadmin/phpmyadmin (https://github.com/phpmyadmin/docker)

All of these docker images are well documented and maintained on Docker Hub (hub.docker.com), with the source maintained on GitHub (github.com).  The total overhead comes to about 600 MB when loaded on a minimal Debian 9 (Stretch) Linux system.
___
