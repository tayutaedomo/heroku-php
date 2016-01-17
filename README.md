# heroku-php
[ ![Codeship Status for tayutaedomo/heroku-php](https://codeship.com/projects/c2862f10-9e49-0133-c94c-2a763bc2b06b/status?branch=master)](https://codeship.com/projects/127723)

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

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
```
$ heroku login
$ heroku git:remote -a <your app name>
$ git push heroku master
```

## Heroku Dashboard
- https://dashboard.heroku.com/


# Source
## [index.php](https://github.com/tayutaedomo/heroku-php/blob/master/web/index.php)
Show page links.

## [phpinfo.php](https://github.com/tayutaedomo/heroku-php/blob/master/web/phpinfo.php)
Show phpinfo.

