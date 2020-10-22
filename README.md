## Setting up Laravel + Vue
laravel new vuejstodo
cd vuejstodo
composer require laravel/ui
php artisan ui vue --auth

npm install 


npm run watch // Build
php artisan serve // Serve

## .env Settings
// Important .env Settings (Local)
Host	localhost
Port	3306
Benutzer	root
Kennwort	root
Socket	/Applications/MAMP/tmp/mysql/mysql.sock

## Connecting to DB
php artisan make:model Todo -mcr  // Creating Mfile C and R
php artisan migrate               // Migrate to DB



# Laravel REST APi for CRUD operations

2. Install composer packages
```
$ composer install
```

3. Create and setup .env file
```
make a copy of .env.example and rename to .env
$ php artisan key:generate
put database credentials in .env file
```

4. Migrate and insert records
```
$ php artisan migrate
$ php artisan tinker
$ factory(App\Customer::class, 100)->create();
```



# Important Notes



