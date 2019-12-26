## Lepro-site Install

- composer install
- sudo chmod -R 0777 storage && sudo chmod -R 0777 bootstrap/cache
- cp .env.example .env
- php artisan key:generate
- php artisan storage:link
- npm install
- npm run dev