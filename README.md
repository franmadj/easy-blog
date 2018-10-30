
# Easy Blog Development Environment

## Prerequisites

- [node.js & npm](https://nodejs.org/)
- [laravel](http://laravel.com/)
- [composer](https://getcomposer.org/)
- PHP >= 7.1.3
- OpenSSL PHP Extension
- PDO PHP Extension
- Mbstring PHP Extension
- Tokenizer PHP Extension
- XML PHP Extension
- Ctype PHP Extension
- JSON PHP Extension



## Installation


mv  .env.example .env

composer install

php artisan key:generate

php artisan migrate

php artisan db:seed

npm install

npm run production/dev

sudo chown -R www-data:www-data storage

sudo chmod -R g+w storage

php artisan storage:link

