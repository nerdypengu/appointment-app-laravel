<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>


<h2>Used HTML Templates</h2>
Main website : https://www.free-css.com/free-css-templates/page270/one-health
Admin Dahsboard : https://github.com/BootstrapDash/corona-free-dark-bootstrap-admin-template

<h2>Features</h2>
- Email verification
- Email notification
- Sending email to user
- Admin dashboard

<h2>Run it locally</h2>
<p> 1. Clone the project </p>
<code>git clone https://github.com/nerdypengu/appointment-app-laravel.git project-name</code>
<p>2. Go to the project directory</p>
<code>cd project-name</code>
<p>3. Copy .env.example file to .env and edit database credentials there </p>
    <code>composer install</code>
    <code>php artisan key:generate</code>
    <code>php artisan migrate:fresh --seed</code>

Login :
username :admin@gmail.com
password : password

If Login not possible, please reregister

<h2>Important Notice</h2>
For Sending email to user feature,
You need to create app password for your gmail and use that password in your project env  MAIL_PASSWORD.
For creating app password you check this video : https://www.youtube.com/watch?v=J4CtP1MBtOE

<p>There are still some bug here and there, please forgive me. I will bash those bugs later on. </p>
