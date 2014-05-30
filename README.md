Project Name : Custom Google Map Creator

Project Language : HTML,CSS,PHP (V-5.3),Javascript

Database : MySQL


Project Details : 

This is a project powered by Google Map. The core language is PHP and Front-end is handled by HTML,CSS and Javascript (with Jquery 1.7.2).
Here user can create different size of the map and put marker, set info for each marker, create line and then can save it. After saving user
will get a html code. If the user put that code in his site the map will be displayed in his website with full details as he created here.


Instructions:

Installing Database:

To use it you need a mysql database. At phpmyadmin on database you need to create a database (in localhost) and then in that database you just need
to export the database file named "map.sql" located in "Main File/Database Structure" folder. After exporting you just need to change the database config details. To do this

You need to go to the "Main File/functions" folder and need to edit the file named "database.php". You'll find 4 variable there.

$DatabaseHost = "localhost"; #Database host address
$DatabaseUser = "root";      #Database user name
$DatabasePass = "";          #Database user password
$DatabaseName = "map";       #Database name

and you are done.


Instruction for changing Encryption and Decryption Key changing:

There is a little encryption/decryption part by which the access of the map is handled. You can set your own key for that. To do this
You need to go to the same folder as given abobe ("Main File/functions") and open "encryption_decryption.php" file and edit it in this section:

Find "var $skey" and change it to your own key. and you are done.
