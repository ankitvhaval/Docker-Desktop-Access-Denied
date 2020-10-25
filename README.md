# Docker-Desktop-Access-Denied
If you facing issue - You are not allowed to use Docker . You must be in the "docker-users" group. for Domain Users

(This process need to be done by Domain Admin)

Information
SO: Windows 10 Pro

Log in to the Domain User Account in Windows 

Search for Computer Management in start menu and run it as domain administrator/administrator

Go to Computer Management - then Local Users and Groups

now go into the Groups folder and search for Docker-users group

go to Docker-users group properties and add domain user in it

and Click on OK, now close computer managment and start your docker it will start without error.

