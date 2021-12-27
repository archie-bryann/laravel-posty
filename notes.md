# To start a project:
composer create-project laravel/laravel example-app

cd example-app

php artisan serve

# To make a model
php artisan make:model Product --migration

# To migrate
php artisan migrate

# To create Controller
php artisan make:controller Product --api 
- --api to add crud methods

# To get the route list
php artisan route:list

# To get sanctum
composer required laravel/sanctum
php artisan migrate
php artisan vendor:publish --provider="Laravel\Sanctum\SanctumServiceProvider"