# heroku-php
Execute php script on Heroku.

## References
- https://devcenter.heroku.com/articles/php-support
- https://devcenter.heroku.com/articles/deploying-php

- https://devcenter.heroku.com/categories/php


# Local development
## Setup
Setup heroku development environment on your local.
- https://devcenter.heroku.com/articles/getting-started-with-php#set-up

Get source code and install packages.
```
$ git clone git@github.com:tayutaedomo/heroku-php.git
$ cd heroku-php
$ curl -s https://getcomposer.org/installer | php
$ php composer.phar install
```

## Console
```
$ heroku run "php -a"
```
See: https://devcenter.heroku.com/articles/getting-started-with-php#start-an-interactive-shell


# Deploy


# Source
## [index.php](https://github.com/tayutaedomo/heroku-php/blob/master/web/index.php)
Show page links.

## [phpinfo.php](https://github.com/tayutaedomo/heroku-php/blob/master/web/phpinfo.php)
Show phpinfo.

