# Mysql on Linux
##### command for mysql server installation on ubuntu
* sudo apt-get install mysql-server
##### Issues faced and resolved while installation
https://askubuntu.com/questions/364404/e-unable-to-fetch-some-archives-maybe-run-apt-get-update-or-try-with-fix-mis

Questions : how to check if mysql-server , mysql-client is installed on ubuntu?

##### command mysql client installation  on ubuntu
* apt install mysql-client-core-8.0
##### connecting to mysql via connection string
* Sample connection string
*mysql -u admin -padmin123 -h database-1.cdps5t3rrsml.ap-south-1.rds.amazonaws.com -P 3306 -D RaghuDB*
 ###### Error -ERROR 2003 (HY000): Can't connect to MySQL server on 'payrolldb.cdps5t3rrsml.ap-south-1.rds.amazonaws.com:3306' (11)
 * resolution : on database security vpc , modify the inbound rule to get public access
 
 # Notes
* Queries should end with semicolon on mysql terminal
* Should use 'exit' command to come out of mysql terminal
* In mysql connection string, password should not have space after -p (command argument)
* show databases;

* Press the ESC key for normal mode.
* Press i Key for insert mode.
* Press :q! keys to exit from the editor without saving a file.
* Press :wq! Keys to save the updated file and exit from the editor.
* Press :w test.txt to save the file as test.txt
