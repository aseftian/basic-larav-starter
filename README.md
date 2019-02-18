# basic-larav-starter
My Starter Template Laravel

### Penggunaan
``` bash
# clone repo
$ git clone git@github.com:aseftian/basic-larav-starter.git

# masuk ke dalam direktori aplikasi
$ cd basic-larav-starter

# install composer dependencies
$ composer install

# generate key aplikasi
$ php artisan key:generate

# generate jwt secret
$ php artisan jwt:secret

# install db migrasi
$ php artisan migrate

# insert initial data db
$ php artisan db:seed

# install npm dependencies
$ npm install

# run development localhost:8000
$ php artisan serve
$ npm run watch

# build untuk production
$ npm run prod
```
