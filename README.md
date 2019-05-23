## simple-nginx-php
Simple Nginx + PHP container image with Supervisord

Build

$ docker build -t matheuscarino/simple-nginx-php:0.1 .

Run

$ docker run -p 80:8080 matheuscarino/simple-nginx-php:0.1

Test

The static html page on http://localhost/