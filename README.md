# Ecommerce Laravel 9 vuejs 3 api composition

Create a simple Ecommerce with Laravel 9 and Vuejs 3.

## Technologies & versions

- Laravel 9.24.0

## Add this vhost
```
<VirtualHost *:80> 
    DocumentRoot "YOUR_WEB_ROOT_SERVER/www/laravel-vuejs3-ecommerce/public/"
    ServerName laravel-vuejs3-ecommerce.test
    ServerAlias *.laravel-vuejs3-ecommerce.test
    <Directory "YOUR_WEB_ROOT_SERVER/www/laravel-vuejs3-ecommerce/public/">
        AllowOverride All
        Require all granted
    </Directory>
</VirtualHost>
```

## Install
```
- Clone project 
- Make: composer install
- Create a database named laravel-vuejs-ecommerce
- Make: php artisan migrate
- Make: php artisan migrate --seed
- Make: npm install
- Make: npm run build
- Go to project localhost url ex: http://laravel-vuejs3-ecommerce.test
```