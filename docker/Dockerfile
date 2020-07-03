FROM asclinux/linuxforphp-8.2-ultimate:7.0-nts
RUN composer self-update
RUN cd / && composer create-project laravel/laravel:~5.4 app
WORKDIR /app
RUN composer install

CMD php artisan serve --host=0.0.0.0 --port=80
