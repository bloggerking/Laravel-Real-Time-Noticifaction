create .env file from .env.example

Set Redis setting in .env file

    BROADCAST_DRIVER=redis
    REDIS_HOST=localhost
    REDIS_PASSWORD=null
    REDIS_PORT=6379
    LARAVEL_ECHO_PORT=6001
Run below command to install dependency

    npm install
Install composer dependency

    composer update
Now start laravel echo server using below command

    laravel-echo-server start
Now start laravel

    php artisan serve

[See Detail Step wise description](http://blogsaura.com/laravel-real-time-notification/)