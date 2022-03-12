# php-fpm-docker
PHP-FPM docker image

This is only a PHP-FPM image, it doesn't have NGINX or APACHE.

You may need to build/run it with Docker Compose alongside NGINX/APACHE, and MySQL as needed.

To build:

docker build .

To run / enter PHP FPM:

docker container run -it <image id> bash

You can then run composer scripts as you like
  
