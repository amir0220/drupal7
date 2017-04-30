Please follow the steps below in order to get this project up and running:

1. Clone this git repository (https://github.com/amir0220/drupal7.git) to somewhere inside your webroot.
2. This will create a dir/project named "drupal7" with all required files and the site can be accessed at PATH_TO_CLONED_LOCATION/drupal7.
3. The MySQL database dump file "drupal7.sql" can be accessed/downloaded from my google drive at https://drive.google.com/file/d/0B7QAsxI9yMViTmlpd1dJbUxqWk0/view?usp=sharing
4. Import/Execute the drupal7.sql file to your MySQL database server. This will create the database named "drupal7" for this site and all database tables and data in it.
5. Create a MySQL database user named "drupal7" with password "drupal7" on your database server. Assign at least SELECT, INSERT, UPDATE, DELETE, DROP privileges for this user to the drupal7 database.
6. If the database server is not on localhost, change the database settings for the site by opening the settings.php file located at drupal7/sites/default/settings.php. On line #252 set the value of "host" from "localhost" to the IP_ADDRESS where the database server is located. 

That should be all, and the website should be up and running.

Please do contact me if you have any trouble running the website.

Thanks.
