# LAMP stack setup

Expanding on my initial server setup, I setup a LAMP stack, installing and configuring Apache, MySQL and PHP, creating a simple SQL table viewable from a webpage.

## Installing Apache, MySQL and PHP

First I install Apache and confirm that it's working.

![ApacheUp](screenshots/Apache_Up.png)

Next I installed MySQL.


![SQL_Installed](screenshots/SQL_installed.png)

Then I created a user in MySQL, and granted permissions.

![User_permissions](screenshots/User_permissions.png)

After that, I installed PHP, created a file, and viewed it in a browser to confirm that it was working.

![PHP_up](screenshots/PHP_up.png)

## Creating database and devices table and inserting a row

After deleting that test page, I created a database called 'homelab' and created a table for 'devices'

![TableCreated](screenshots/Table_created.png)

I added rows for three devices (after adding the row in the image, I went back and added rows for 'router' and 'windows server', the latter of which is not yet extant).

![RowInserted](screenshots/Row_inserted.png)


## Creating webpage with PHP and snapshotting

I created and configured php file for my devices table, and confirmed that it was up and running.

![WebpageUp](screenshots/Webpage_Up.png)

Lastly, I took a new snapshot in Virtualbox.

![Snapshot2](screenshots/Snapshot2.png)



