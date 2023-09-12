# Usa una imagen base de PHP-FPM
FROM php:7.4-fpm

# Establece el directorio de trabajo
WORKDIR /var/www/html

# Copia el código fuente a la imagen
COPY services/php-progress /var/www/html

# Instala las dependencias de PHP si es necesario
# RUN composer install

# Expón el puerto en el que se ejecutará PHP-FPM
EXPOSE 9000

# Comando para ejecutar PHP-FPM
CMD ["php-fpm"]
