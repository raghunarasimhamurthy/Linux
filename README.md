# Linux

## Linux Command Details with switches
[explainshell.com](https://explainshell.com/explain/1/ls)

## Environment Variables
[TechMint](https://www.tecmint.com/set-unset-environment-variables-in-linux/)

## check Linux OS details via terminal
* cat /etc/os-release

##  Shells 
* Shells are command interpreters. They are applications that provide users with the ability to give commands to their operating system interactively, or to execute batches of commands quickly. In no way are they required for the execution of programs; they are merely a layer between system function calls and the user.
[click here for more info](http://mywiki.wooledge.org/BashGuide)

## What are the few Editors available in Linux environment
*  vi editor, vim editor, Emacs editor, kate editor, Gedit editor, GNU nano editor

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
![alt text](https://github.com/raghunarasimhamurthy/Linux/blob/0631be6d1f1708a7386544961b7768759d81f083/abc.png?raw=true)


## apt command
* Install, Manage, Update, Remove Packages on linux systems 

## Ubuntu - Terminal scroll issue : ubuntu clear command does not initialize scrollbar
* What you want is to type CTRL+L instead of clear. This will send a "Form Feed" to the terminal. Basically it will move everything up the height of the terminal window clearing the screen without affecting your scrollback.

## Deamon
* A daemon (also known as background processes) is **a Linux or UNIX program that runs in the background**. Almost all daemons have names that end with the letter "d". For example, httpd the daemon that handles the Apache server, or, sshd which handles SSH remote access connections. Linux often start daemons at boot time.


