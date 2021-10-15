## Laravel Tailwind Admin  Dashboard
Minimal - very minimal dashboard for laravel admin Using Blade's UI Kit and Icons. JetStream for authentication and Tailwind CSS. using Livewire Datatables.Made use also of Livewire components.



### Important files

 - [resources/css/app/css](\resources\css\app.css)
 - [resources/views/layouts/admin.blade.php](\resources\views\layouts\admin.blade.php)

The layouts are in the ```resources/views/components/ui``` folder and the [resources/views/components/admin-sidebar.blade.php](\resources\views\components\admin-sidebar.blade.php) file

### Resources
 - [Blade Templates](https://laravel.com/docs/8.x/blade.html)


Install dependencies
 ```bash
 composer install
 ```
 ```bash
 yarn
 ```
1. Copy or rename .env.example into .env.
2. Create an empty database and type it's credentials into your .env file.
3. Generate an APP_KEY:

```
php artisan key:generate
```

1. Migrate and seed the database:

```
php artisan migrate --seed
```



 Run serve

 ```bash
 php artisan serve
 ```
 Run watch
 ```bash
 yarn watch
 ```
and access the [/admin](http://localhost:3000/admin) route
