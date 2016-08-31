# docker-php5-fpm

Dockerfile and conext for creaing custom fpm image.
This image contain two custom builded deb packages:
* icu_57-1_amd64.deb
* php5-intl_3.0.0-1_amd64.deb

This packages fix some problems with internationalization.

# Versions

```
# php -r "phpinfo();" | grep -A 10 PECL

...
intl

Internationalization support => enabled
version => PECL-3.0.0
ICU version => 57.1
ICU Data version => 57.1
...
```

# Additional info

* [php intl](http://php.net/manual/en/intro.intl.php)
* [icu](http://site.icu-project.org/)
