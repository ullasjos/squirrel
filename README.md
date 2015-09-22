SQUIRREL WHISPERERS
===================
Austin’s own Squirrel Whisperers are poised for breakout success with the release of their latest single, “Devops Overlord,” receiving heavy airplay on regional radio stations and online streaming services.

Prerequisites
--------------

- Oracle Virtualbox
- Vagrant 

Installation with Vagrant
-------------------------

Assumptions 
	- host folder; /var/www/sqbox
	- target folder; /var/www/

Steps
	- cd /var/www/ 
	- git clone https://github.com/ullasjos/squirrel.git sqbox
	- cd sqbox/VagrantBox 
	- vagrant up

Note: default IP will be 192.168.56.109 
add the following line in the host file of your local machine

192.168.56.109 local.sqbox 
to your local machine's host entry

type http://local.sqbox in your address bar
