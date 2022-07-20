<h1>Autenticação com Laravel Breeze</h1>

-Laravel Framework 8.37.0

<b>Note:</b>
<br />

Usaremos $ para descrever os comandos que serão usados ​​com o usuário comum.

Usaremos # para descrever os comandos que serão usados ​​com o superusuário.

1- Execute os seguintes comandos em sequência para implantar o projeto em um desenvolvimento
meio Ambiente:

$ cp .env.example .env

2- Crie e configure um banco de dados, então:

$ composer install

$ npm install

$ npm run dev

$ php artisan key:generate

$ php artisan migrate

3- Em seguida, você pode navegar para / login ou / URLs de registro do seu aplicativo em seu
navegador da web. Todas as rotas do Breeze são definidas dentro do arquivo routes / auth.php
Arquivo.

<b>Baseado no exemplo</b> -> https://laravel.com/docs/8.x/starter-kits#laravel-breeze