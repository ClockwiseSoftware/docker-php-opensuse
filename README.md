# docker-php-opensuse

# Desription

Docker image on opensuse:42.2 with php-fpm 7.1.14

- iconv 
- soap
- intl 
- calendat
- curl
- mbstring
- mcrypt
- gd
- bz2
- zlib
- pcntl
- exif
- bcmath
- zip
- pdo_mysql
- mysqli
- openssl
- ftp
- imap
- xmlrpc
- xsl
- opcache
- pdo_sqlite
- soap


Can use `latest` tag for local development.

Using oficcial opensuse container.

Include zip git unzip p7zip unrar wget make

With php utilites: composer, phpunit, pear

With locale en_US.utf8 and UTC timezone

# Example 
Container for using php-fpm with nginx

```yml
FROM clockwise/docker-php-opensuse

WORKDIR /var/www
```