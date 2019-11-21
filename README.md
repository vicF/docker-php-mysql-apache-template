# docker-php-mysql-apache-template
This is a quick start template for docker environment with PHP, MySQL, Apache, Xdebug. 
Docker files are in "Docker" subfolder
Inspired by https://dev.to/veevidify/docker-compose-up-your-entire-laravel-apache-mysql-development-environment-45ea

Download this template and rename folder to your application name. 
Copy .env.example to .env
Edit .env file to replace "MyApplication", "MyDatabaseName", "myapplication-db" with respective names
Edit Docker\docker-compose.yml to rename "myapplication" and change pors if needed

You can use start, stop scripts in linux/OS-X environments. 

