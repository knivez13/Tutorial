**CRATE_PROJECT_WITH_LOGIN_AND_REGISTRATION**
* "composer create-project --prefer-dist laravel/laravel (name_of_project)" -- create new project
* setup the database on .env file
* open terminal
* "composer require laravel/ui" -- install laravel ui interface
* "php artisan ui bootstrap --auth" -- create a user login with design and function
* "php artisan migrate" -- create a database and connection to the server
* "npm install" -- install all node js package need for laravel
* "npm run dev" -- run for gui server
* add new terminal
* "php artisan serve" -- open a server

**CRATE_MODEL_MIGRATION_CONTOLLER_VIEWS_AND_EDIT_ROUTES**
* "php artisan make:model Branch -mrc" -- create model with migration and controller that have resource
* edit the branch migrate file for the database update under database->migrations
* "php artisan migrate:refresh" -- update the database
* edit the model of branch under app->Models
* edit the controler of the branch under app->Http->Controllers
* add route of the branch on routes->web.php
* create folder under resources->views name branch under that create file named create, edit, index, list and extension of .blade.php
* start to configure the controller and design of the views


Next tutorial is validation