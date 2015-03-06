# QueueStats2015
Simple yet informative queue stats viewer.  Works in all major distros.

Instructions:

In FreePBX: Admin>Module Admin> Make sure PHPAGI Config module is installed. If not, install it.

Goto Settings>Asterisk Manager Users> Add Manager with a name like queuestats and a complex password. ReadRead/Write all. Submit changes.

Goto Settings>PHPAGI Config> under Asterisk API settings Choose Manager: queuestats. Submit changes.

Browse CentOS to /var/www/html/. Create a folder called queuestats (or whatever you would like) and drop in index.php

Browse to http://FreePBXip/queuestats/ and there it is!

NOTE: Queue members must be dymamic.  In your queue settings make sure to set reset queue stats nightly/weekly.  It's basic PHP very easy to customize to your cosmetic likings.
