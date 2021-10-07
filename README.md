# docker_mysql_testdb

The purpose for this github repository is to provide people who would like to practice <br>
with SQL to host a simple database with an .sql file backup called "employees" found from <br>
a source that includes the following authors, with sample data from Aalborg university: <br>
-  Fusheng Wang and Carlo Zaniolo
<br>
<br>
The .sql file is loaded as a volume mount as the initial database for the docker entry point.

installation procedure
-----------------------

1. install docker and docker-compose<br>
2. concatenate the contents of split files in the db-dump folder into a file called "employees.sql"<br>
     a. cat db-dump/x* > employees.sql <br>
3. run "docker-compose up" from the root of this directory
