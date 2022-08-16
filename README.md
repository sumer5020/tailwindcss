# tailwindcss
tailwind Views for laravel/ui compatable with Laravel 9.0+

## Usage

1. Fresh install Laravel >= 9.0 and `cd` to your app.
2. Install tailwindcss from source
3. Install this preset via `composer require sumer5020/tailwindcss`

### Authentication

1. Use `php artisan ui tailwindcss --auth` for the basic preset, auth route entry, and Tailwind CSS auth views in one go. (NOTE: If you run this command several times, be sure to clean up the duplicate Auth entries in `routes/web.php`)
2. `npm install && npm run dev`
3. Configure your favorite database (mysql, sqlite etc.)
4. `php artisan migrate` to create basic user tables.
5. `php artisan serve` (or equivalent) to run server and test preset.