# MUXU 

Muxu is a group project (4 people), developped in 6 weeks during my studies at Wild Code School. 
It's a fictive e-commerce website, specialized in the sale of artwork.

[![home-muxu.png](https://i.postimg.cc/Hn9vXfpg/home-muxu.png)](https://postimg.cc/JHtQWYD6)

# HOW TO USE IT

1. Clone the repo from Github.
2. Run `composer install`.
3. Create *config/db.php* from *config/db.php.dist* file and add your DB parameters. Don't delete the *.dist* file, it must be kept.
```php
define('APP_DB_HOST', 'your_db_host');
define('APP_DB_NAME', 'your_db_name');
define('APP_DB_USER', 'your_db_user_wich_is_not_root');
define('APP_DB_PWD', 'your_db_password');
```
4. Import `muxu.sql` in your SQL server,
5. Run the internal PHP webserver with `php -S localhost:8000 -t public/`.
6. Go to `localhost:8000` with your favorite browser.

# BUILT WITH

We made this project from scratch, and we followed the SCRUM model (agile methodology) : 
* Mockup 
* Data modeling
* Development with :
    * MVC Pattern
    * Php 7
    * MySQL
    * Bootstrap 4.5

# AVAILABLE FEATURES

[![product-page-muxu.png](https://i.postimg.cc/J7TMfgNg/product-page-muxu.png)](https://postimg.cc/Hj7q56P4)

* User account with wishlist feature
* Purchase tunnel (basket, stripe)

[![admin-muxu.png](https://i.postimg.cc/dt5MkTHx/admin-muxu.png)](https://postimg.cc/LngQGhMt)

* Admin area where you can add new product, desactivate them, choose an artist to 
put on the home page, add/update some categories for your products. Admin user also have access to a dashboard to follow stocks, sales, products most liked.
