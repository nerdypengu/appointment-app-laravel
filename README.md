<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>


#Used HTML Templates
Main website : https://www.free-css.com/free-css-templates/page270/one-health
Admin Dahsboard : https://github.com/BootstrapDash/corona-free-dark-bootstrap-admin-template

#Features
- Email verification
- Email notification
- Sending email to user
- Admin dashboard

#Run it locally :
1. Clone the project
 ``` git clone https://github.com/nerdypengu/appointment-app-laravel.git project-name ```
2. Go to the project directory
```cd project-name```
3. Copy .env.example file to .env and edit database credentials there
    ```composer install
    php artisan key:generate
    php artisan migrate:fresh --seed ```

Login :
username :admin@gmail.com
password : password

If Login not possible, please reregister

#Important Notice
For Sending email to user featuree,
You need to create app password for your gmail and use that password in your project env  MAIL_PASSWORD.
For creating app password you check this video : https://www.youtube.com/watch?v=J4CtP1MBtOE

There are still some bug here and there, please forgive me. I will bash those bugs later on.
