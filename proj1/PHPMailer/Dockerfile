
FROM php:7.4-apache

WORKDIR /var/www/html


COPY . /var/www/html
EXPOSE 80

# Start Apache in the foreground
CMD ["apache2-foreground"]