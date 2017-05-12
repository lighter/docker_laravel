# Docker & Laravel

ref: [Creating Laravel PHP Application in Docker: Step-by-Step Guide](https://www.codementor.io/patrickfohjnr/developing-laravel-applications-with-docker-4pwiwqmh4)

## Step 1. Install Laravel

ref:

* [Composer](https://getcomposer.org/)
* [Laravel](https://laravel.com/docs/5.4/installation)

```
$ composer global require "laravel/installer"

# 確認 $HOME/.composer/vendor/bin 已經加入到 PATH 

# 1. laravel command create project
$ laravel new blog

# 2. composer command create porject
$ composer create-project --prefer-dist laravel/laravel blog

# test laravel project is work.
$ cd blog
$ php artisan serve
```

## Step 2. make `docker-compose.yml`


