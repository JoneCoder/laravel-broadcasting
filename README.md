# Laravel Broadcasting

Simple steps to Broadcasting your **Laravel** app

**Laravel php Docker nginx MySQL phpmyadmin**

    .
    ├── dockerfiles
    │   ├── nginx
    │   │   └── default.conf  
    |   └── nginx.dockerfile
    |   └── php.dockerfile
    ├── mysql
    ├── src
    └── docker-compose.yml

    3 directories, 4 files

#### Development Stuffs:

<img height="48" src="files/img/php-original.svg" alt="php"> <img height="48" src="files/img/laravel-plain-wordmark.svg" alt="Laravel"> <img height="48" src="files/img/vue-original.svg" alt="vue"> <img height="48" src="files/img/mysql-original.svg" alt="mysql"> <img height="48" src="files/img/docker-original.svg" alt="Docker"> <img height="48" src="files/img/nginx-original.svg" alt="nginx"> <img height="48" src="files/img/git-original.svg" alt="git">

#### Installation:

>First clone this repository for command:<br/>
<code>$ git clone https://github.com/JoneCoder/dockerize-broadcasting.git</code>


>Second change the directory this command:<br/>
<code>$ cd dockerize-broadcasting/</code>

>Make mysql directory this command:<br/>
<code>$ mkdir mysql</code>

>Build & run project on detach mode with "Docker" this command:<br/>
<code>$ docker-compose up -d --build</code>

>Now change the directory this command:<br/>
<code>$ cd src/</code>

>Then copy the .env.example file to .env flowing command:<br/>
<code>$ cp .env.example .env</code>

>Now update composer for install laravel vendor:<br/>
<code>$ docker-compose run --rm composer install</code>

>If composer installing done than you generate application key for this command:<br/>
<code>$ docker-compose run --rm artisan key:generate</code>

>Migrate a database run the flowing command:<br/>
<code>$ docker-compose run --rm artisan migrate</code>


>Install and run npm this command:<br/>
<code>$ docker-compose run --rm npm install && npm run dev</code>


>If you're done all stuffs than open your favorite browser hit localhost port 8080:<br/>
<code>http://localhost:8080</code>

>Enjoy this service.