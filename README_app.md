# A Dockerized Microservice Application environment

## I. App Container
* PHP 8.1.7
* Laravel 9.18.0
* PHPStan
    * [PHPStan document URL](https://phpstan.org/user-guide/getting-started)
    * Run composer script inside of app container: `bin/composer run phpstan`
* PHP_CodeSniffer
    * [Configuration Options](https://github.com/squizlabs/PHP_CodeSniffer/wiki/Configuration-Options)
    * Run composer script inside of app container: `bin/composer run php-cs`

## II. DB Container
* MySQL 8.0.29

# Initialized URL
If the app container publish port change, then change the url port accordingly.
* Laravel welcome page: http://localhost:8888
* PHP Info page: http://localhost:8888/phpinfo.php