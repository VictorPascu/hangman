# hangman
A Hangman game - single or duel modes

## Local Setup
You need PHP, MySQL and Composer installed on your machine. 

For Windows, you can use XAMPP to skip PHP/MySQL config.

You can get Composer at:
https://getcomposer.org

In the project root folder, run: 
`composer install`

Within `global_config.php`, set the `BASE_URL` to your server, i.e. `http://localhost:8000/`. The browser protocol and trailing slash are important.

Configure your MySQL user settings in `global_config.php`, then execute the statements in the SQL folder in the hangman DB;

To start the project, while in the root folder, run:

`php -S localhost:8000 -t public/`
