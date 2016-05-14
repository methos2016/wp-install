# wp-install.sh

Installation script for the latest WordPress on Ubuntu 14.04.  
Script goes through these procedures: create new database, download wordpress, modify wp-config.php, set permissions, create .htaccess file, create robots.txt file, download some wordpress plugins.

## Usage

Go inside the directory planned for the WordPresse installation. Download the script with `curl` and run it with `bash` command.

    curl -L -o 'wp-install.sh' https://raw.githubusercontent.com/WebPraktikos/wp-install/master/wp-install.sh
    bash wp-install.sh

*Notice:* If needed use `sudo` before command to escalate privilages.

After the script is executed, a few questions will be asked about MySQL database reserved for WordPress installation. If no previous database has been created, just enter desired info and the database will be created for you.
