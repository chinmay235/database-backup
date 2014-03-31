database-backup
===============

This code helps to backup your database and tables by the user end.

backup_tables('localhost','user','pass','databasename');

If you want to download a single table name please add a extra parameter on backup_tables() function.

`backup_tables('localhost','user','pass','databasename','table_name);`

Of course, you'll need to provide database credentials to the function, as well as an array of tables you'd like to backup. If you provide a "*" or no tables, a complete database backup will run. The script does the rest!

