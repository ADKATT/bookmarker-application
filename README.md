# Installation & Setup

1. Download [Composer](http://getcomposer.org/doc/00-intro.md) or update `composer self-update`.
2. Download this repository - `git clone git@github.com:cakephp/bookmarker-application`
3. Install dependencies with composer - `composer install`.
4. Add the schema to a new database.
5. Configure your database credentials in ``app.php``. Make sure to use the same database name as in step 4.
6. Start the server `bin/cake server -p 8765`.
7. Go to http://localhost:8765 in your browser.
