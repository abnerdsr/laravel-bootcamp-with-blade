# Laravel Bootcamp utilizando Blade

## Requerimentos mínimos

PHP 8.2 (https://laravel.com/docs/11.x/deployment#server-requirements)
Composer 2.7 

## Instalando o projeto

Clone o respositório
```sh
git clone git@github.com:abnerdsr/laravel-bootcamp-with-blade.git
```

Instale as dependencias
```sh
composer install
npm i
```

Rode as migrations
```sh
php artisan migrate
```

Faça o build do front
```sh
npm run build
```

Rode os workers das filas
```sh
php artisan queue:work
```

Agora abra um outro terminal para manter o worker das filas rodando

Rode o servidor da aplicação
```sh
php artisan serve
```

Pronto, ja pode acessar o projeto em
```text
http://127.0.0.1:8000
```