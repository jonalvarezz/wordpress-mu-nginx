# Wordpress Nginx Configuration
Files to create a Wordpress Multisite with subdomain support in Nginx.

This configuration files have been builded from many sources, taking the best parts/tips and most updated snippets. Some of the source are:
* [Wordpress - Nginx Wiki](http://wiki.nginx.org/Wordpress)
* [Nginx - Wordpres Codex](https://codex.wordpress.org/Nginx)
* [How to Nginx I and II (SPA)](http://blog.jonalvarezz.com/configurar-y-gestionar-sitios-en-nginx/)
* [@perusio wordpress-nginx](https://github.com/perusio/wordpress-nginx) (outdated)
* [Wordpress Multisite with Nginx - wpmudev](http://premium.wpmudev.org/blog/wordpress-multisite-wordpress-nginx/)
* [Wordpress Nginx - rtCamp](https://rtcamp.com/wordpress-nginx/tutorials/)


## Pre requisites
* A web server running some Linux distribution. Tested in Archlinux and Ubuntu 14.04
* `nginx`, `php-fpm` and `mysql` (or `mariadb`) have been installed in the server

## Installation
Override this files with the content in `/etc/nginx/`, and make sure to adjust your data.

