1 Innoscripta-Pizza

A online Pizza ordering application build with React for the front End  and PHP laravel For the backend


2 Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.



3 Prerequisites

```sh
3.1 [npm](https://www.npmjs.com/get-npm) 
3.2 [php](http://php.net/)
3.3 [composer](https://getcomposer.org/)

```


4 Installing



4.1 Front-end part

Install the required packages and run the local server
```sh
- npm Install
- npm start
```

4.2 Back-end part

You should go to API directory 
```sh
cd api 
```
4.2.1 Install laravel framework

```sh
composer global require "laravel/installer"
```

4.2.2 Create a database name innoscripta 


DB_CONNECTION=mysql
DB_HOST=localhost
DB_PORT=3306
DB_DATABASE=innoscripta
DB_USERNAME=root
DB_PASSWORD=


4.2.3 Install the required packages and run the local server

```sh
composer install
```


4.2.4 Generate database tables and relations

```sh
php artisan migrate
php artisan storage:link
php artisan key:generate
php artisan config:cache
php artisan serve
```

NB: there is file innoscripta.sql you can import juste in case because laravel framework need last version of PHP and some modules 



5 Author

Ayoub LACHHAB
This App Build For innoscripta Company 
