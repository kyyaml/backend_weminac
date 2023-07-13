## Installation 

1. Copy .env.example into .env and configure database credentials
2. Navigate to the project's root directory using terminal
3. Run ``` composer install ```
4. Set the encryption key by executing ``` php artisan key:generate --ansi ```
5. Run migrations ``` php artisan migrate ```
6. ``` php artisan jwt:secret ```
7. ``` php artisan storage:link ```
8. ``` php artisan serve ```   
