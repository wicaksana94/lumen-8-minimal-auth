# Lumen 8 with minimal auth

This project is boilerplate of [Lumen](https://lumen.laravel.com/) micro-framework which include 
basic authentication using api_token in Authorization header, located in AuthServiceProvider.
I hope when you use this boilerplate, you
can speed up your development.

## Installation
Before doing the installation, I recommend you to use **PHP 7.3** or above with **Composer 2.0**

Download the code, then use the [composer](https://getcomposer.org/) to install.

```bash
composer install
```

Make sure your installation is success. 

## Usage
Configure your .env file to set database connection, APP_NAME, APP_KEY, etc.

After that, do a migration
```bash
php artisan migrate
```

If it migrated sucessfully, run lumen with : 
```bash
php -S localhost:8000 -t public
```

Open your Postman app to test the register and login.

![alt text](https://i.ibb.co/hC76rzm/register.png)
![alt text](https://i.ibb.co/3S3zb7x/login-border-fix.png)
![alt text](https://i.ibb.co/VW0vSj0/login-fail-border-fix.png)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


