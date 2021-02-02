<h2> Todolist (Laravel + Vue) </h2>
<hr>
<h3>Instalation and running the app<h3>
cp .env.example .env
composer install
php artisan key:generate
php artisan migrate
php artisan db:seed
php artisan serve
<h3>Configuring the app<h3>
cd resources/frontend/app
npm install
npm run serve | Or doing it by vue UI with -> $vue ui