### Telegram Web Interface for Admin channel

**Install & Startup**:

1. `composer install`
2. `npm install`
3. create you database in mysql (db name - *telegram_web*)
4. `cp .env.example .env` (or copy)
5. config database credits in *.env* file
6. ~~`php artisan migarate`~~ in current version migrations are not allowed
7. `npm run dev`
8. `php artisan serve` (or if no loading styles `php -S localhost:8000 -t public/`)



**Description**

This project - demo project of my course on Laravel in my telegram channel - [@fromidiottojunior](https://t.me/fromidiottojunior)

