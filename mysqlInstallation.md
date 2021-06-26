# Commands for installation of mysql on ubuntu
##### command for mysql server installation on ubuntu
### sudo apt-get install mysql-server
##### Issues faced and resolved while installation
https://askubuntu.com/questions/364404/e-unable-to-fetch-some-archives-maybe-run-apt-get-update-or-try-with-fix-mis

Questions : how to check if mysql-server , mysql-client is installed on ubuntu?

##### command mysql client installation  on ubuntu
### apt install mysql-client-core-8.0


 <br/>
 
* Sample connection string
*mysql -u admin -padmin123 -h database-1.cdps5t3rrsml.ap-south-1.rds.amazonaws.com -P 3306 -D RaghuDB*

* Queries should end with semicolon on mysql terminal
* Should use 'exit' command to come out of mysql terminal
* In mysql connection string, password should not have space after -p (command argument)
* show databases;

* Press the ESC key for normal mode.
* Press i Key for insert mode.
* Press :q! keys to exit from the editor without saving a file.
* Press :wq! Keys to save the updated file and exit from the editor.
* Press :w test.txt to save the file as test.txt
