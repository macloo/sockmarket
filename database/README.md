# The Database

These instructions explain how to set up a new MySQL database to use with these files.

In XAMPP, open phpMyAdmin.

[http://localhost/phpmyadmin/](http://localhost/phpmyadmin/)

Note: If XAMPP is not running, that link is no good. XAMPP must be running.

Databases tab:
* Create database
* Name it *sockmarket*
* Create

Create table:
* Name it *socks*
* Number of columns: 7
* Go

Name the 7 columns:
* id
* name
* style
* color
* quantity
* price
* date

id field:
* Keep the Type INT (integer) because this is a number
* Length: 11
* Index: Change to PRIMARY (only this field has an index)
* Check the tiny box immediately following Index (A_I): This is AUTO INCREMENT; it will assign a new ID number automatically.

name field:
* Type: TEXT
* Length: 20

style field:
* Type: TEXT
* Length: 20

color field:
* Type: TEXT
* Length: 20

quantity field:
* Type: INT
* Length: 20

price field:
* Type: DECIMAL
* Length: 19,4

date field:
* Type: TEXT
* Length: leave blank
* We will use PHP to construct the date, so we will not use the SQL type DATE.

**Save** the database.