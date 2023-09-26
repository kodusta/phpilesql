# Database Backup Script

This is a simple PHP script for creating backups of your MySQL database tables and saving them as SQL files. It can be useful for database maintenance and disaster recovery.

## Usage

1. Make sure you have PHP installed on your server.

2. Modify the database connection details in the script:

   ```php
   $dbhost = 'your_database_host';
   $dbuser = 'your_database_username';
   $dbpass = 'your_database_password';
   $dbname = 'your_database_name';
1. Upload this script to your web server or the server where your database is hosted.

2. Access the script using your web browser. For example:

   http://your-website.com/backup-script.php
3. The script will create a backup of all tables in your database and save them as separate SQL files in the same directory as the script.
4. You can download the backup files for safekeeping.

# Important Note
Make sure to protect this script from unauthorized access, as it can potentially expose sensitive database information.
# License
This project is licensed under the MIT License. See the LICENSE file for details.

