# Testing Laravel 9 REST API Authentication using Sanctum

It's just that... Just testing from the following tutorial:
https://www.itsolutionstuff.com/post/laravel-9-rest-api-authentication-using-sanctum-tutorialexample.html
Laravel 9 REST API Authentication using Sanctum Tutorial

## Getting Started

Just read the tutorial:
https://www.itsolutionstuff.com/post/laravel-9-rest-api-authentication-using-sanctum-tutorialexample.html

### For the most impatient learners

Clone this project:

````
git clone https://github.com/tcrurav/LaravelSanctum.git
````

Create a .env. You can just copy .env.example to .env, and edit the database credentials.

After that create the database in MySQL.

Install Laragon and from there:

````
composer install
php artisan migrate
php artisan serve
````

And now just try all the POSTMAN requests:

![screenshots](https://github.com/tcrurav/LaravelSanctum/blob/master/screenshots/01-register.png)

__________________________________________________________

![screenshots](https://github.com/tcrurav/LaravelSanctum/blob/master/screenshots/02-login.png)

__________________________________________________________

![screenshots](https://github.com/tcrurav/LaravelSanctum/blob/master/screenshots/03-create.png)

__________________________________________________________

![screenshots](https://github.com/tcrurav/LaravelSanctum/blob/master/screenshots/04-read.png)

__________________________________________________________

![screenshots](https://github.com/tcrurav/LaravelSanctum/blob/master/screenshots/05-read-one.png)

__________________________________________________________

![screenshots](https://github.com/tcrurav/LaravelSanctum/blob/master/screenshots/06-update.png)

__________________________________________________________

![screenshots](https://github.com/tcrurav/LaravelSanctum/blob/master/screenshots/07-delete.png)

Enjoy!!!

### Prerequisites

All you need is... some time and...
* Visual Studio Code.
* Laravel 9.
* Laragon.
* MySQL Workbench, to host the database also included in the project.
* PostMan, for the RESTFul tests.
* More hours than you first could think of...

## Built With

* [Visual Studio Code](https://code.visualstudio.com/) - Visual Studio Code Editor.
* [Laragon](https://laragon.org/) - Modern & Powerful - Easy Operation - PHP environment - Similar to XAMMP.
* [MySQL Workbench](https://www.mysql.com/products/workbench/) - The Database used.

## Acknowledgments

* https://www.itsolutionstuff.com/post/laravel-9-rest-api-authentication-using-sanctum-tutorialexample.html. Laravel 9 REST API Authentication using Sanctum Tutorial
* https://www.getpostman.com/. Used to test the RESTFul end points of the project.
* https://gist.github.com/PurpleBooth/109311bb0361f32d87a2. A very complete template for README.md files.