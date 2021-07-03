# Linux

##  Shells 
* Shells are command interpreters. They are applications that provide users with the ability to give commands to their operating system interactively, or to execute batches of commands quickly. In no way are they required for the execution of programs; they are merely a layer between system function calls and the user.
[click here for more info](http://mywiki.wooledge.org/BashGuide)
## How to deploy web application on linux
* switch to root user
* install --yum install httpd
* start		--service httpd start
* should enable the ports - http. by default only ssh is opened
* go to the path var/www/html/ and copy the application files

_Notes helpful while preforming above steps_
* sudo su #su :switch user
* ususallly linux has 3 users - root, normal user and group user
* there is a tool WinSCP to move files into linux server similar to filezilla
* httpd means apache default 
* server manager in windows - yum in lunux
* chmod -- change permission - 777

## why is the difference -- and - in linux command
* A single hyphen can be followed by multiple single-character flags. A double hyphen prefixes a single, multicharacter option.
* tar -czf
* In this example, -czf specifies three single-character flags: c, z, and f.
* Now consider another example:
* tar --exclude

## apt command
* Install, Manage, Update, Remove Packages on linux systems 

## Ubuntu - Terminal scroll issue : ubuntu clear command does not initialize scrollbar
* What you want is to type CTRL+L instead of clear. This will send a "Form Feed" to the terminal. Basically it will move everything up the height of the terminal window clearing the screen without affecting your scrollback.
