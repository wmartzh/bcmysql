# bcmysql
Basic database connection with php and mysql


i hope it will be useful
=======

With this library you can create a basic connection with php and mysql

Implementation

include 'bcmysql/bcmysql-php';
$connection = new BCMysql(hos,user,password); //Host access


if have you a database created, change the database name with your database's name to access it
with the next method

$connection->setDBName(database_name);

If haven't creared a database, you can create a new one with

$connection->createDB(database_name);

Requests

You can also make a requests with the next  method

$connection->requestDB(database_request);

this method returns the results depending on you query
>>>>>>> bcmysql
