# catt-lair
Just an archive and setup script for lair 1.0.5

This is not for everyone.

This will wipe out your existin (but backup) /etc/apache2 directories, replacing them.
This will create a /opt/lair directory and drop the lair files there.
This will move the font-awesome font to /var/www/font-awesome/4.1.0/ and the css files too.
This will run the lair drones python setup.
This will run a2dismod headers -f to remove apache headers.
This addes a lairctl script to /usr/bin/
This will add and set environment vairables for lair for MY setup.  
The file copy to /opt/lair is MY database, you may want to account for that.  You might not like it

Any how, for our uses, git clone https://github.com/catt-lair/catt-lair.git
cd into catt-lair
run install-lair.sh
when it is done, assuming it didn't kiil your system, you can run lairctl start, then connect on https://lairhost:11013

start your pentest
