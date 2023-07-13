Install Laravel

Download the project (or clone using GIT)
Copy .env.example into .env and configure database credentials
Navigate to the project's root directory using terminal
Run composer install
Set the encryption key by executing php artisan key:generate --ansi
Run migrations php artisan migrate 
generate jwt secret by executing  php artisan jwt:secret
install laravel storage link php artisan storage link
Start local server by executing php artisan serve
