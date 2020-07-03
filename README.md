# [![Linux for PHP Banner](docs/images/logo.png)](https://linuxforphp.net/)
# Legacy Laravel Example

To run this application, please enter the following commands after entering your favorite directory:
```bash
git clone https://github.com/andrewscaya/laravel_example
cd laravel_example
composer install
vendor/bin/linuxforcomposer.phar docker:run start
```

Enjoy your Laravel app on port 8181 (http://localhost:8181/)!

To stop the application, please enter the following command:
```bash
vendor/bin/linuxforcomposer.phar docker:run stop-force
```

PLEASE NOTE: As long as you have [Docker](https://www.docker.com/), [Composer](https://getcomposer.org/), [Git](https://git-scm.com/) and [cURL](https://curl.haxx.se/) installed on your computer, this library should work fine.
If on Windows, make sure you are using the linuxforcomposer.phar file contained in the 'vendor/linuxforphp/linuxforcomposer/bin' folder.

Have a lot of fun! :)
