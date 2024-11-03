#pobranie obrazu PHP 
FROM php:7.4.3-fpm-alpine3.11

#kopiowanie katalogu do folderu app
COPY . /app

# Określa, która część kodu będzie podlegała intepreterowi php
# W naszym przypadku jest to folder app, który będzie na serwerze nginx
VOLUME [ "/app" ]