tasks for today

this is a simple task management system made with codeigniter 4

pages

- `/` shows todays tasks
- `/tasks` shows all tasks
- `/profile` shows the demo user
- `/about` shows the developer

setup

1. run `composer install`
2. copy `env` and name the copy `.env`
3. add your mysql database details in `.env`
4. run `php spark migrate`
5. run `php spark db:seed TaskSystemSeeder`
6. run `php spark serve`
7. open `http://localhost:8080`

infinityfree

1. create the database in the infinityfree control panel
2. import `database.sql` using phpmyadmin
3. upload the project files to `htdocs` using ftp
4. make sure `.env` `.htaccess` and the `vendor` folder are uploaded
5. open the website link
