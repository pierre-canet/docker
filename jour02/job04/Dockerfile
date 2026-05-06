FROM php:8.2-apache

COPY index.php /var/www/html/index.php

WORKDIR /app

EXPOSE 80

ENV APP_ENV=production

CMD ["apache2-foreground"]