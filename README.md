# laraveldoublerun
Example of a barebones Laravel + Vue project that shows that the main Vue component "app" runs twice.

Dependencies:
 - PHP > 7.2
 - Composer
Steps to reproduce:
1. Clone repo
2. Open terminal in project directory
3. Run "composer install"
4. Serve the project i.e. "php artisan serve"
5. Open your browser and enter the home page, typically runs on port 8000: "localhost:8000/home"
6. Open developer tools (Ctrl + Shift +  I) and see how the word "app" appears twice.
