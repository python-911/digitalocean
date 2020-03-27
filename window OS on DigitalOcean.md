
# INSTALLING MICROSOFT WINDOWS ON DIGITALOCEAN LINUX DROPLET.

 
~~INSTALLATION OF WINDOWS WAS NEVER EASY ON DIGITALOCEAN ~~ 
 
just kidding its as easy as 1,2,4 Follow this guide -_

1. Create a DigitalOcean Droplets i recommend atleast 2GB ram and choose Ubuntu OS. ( DO NOT USE SSH KEY(

2. Turn off your droplet -> now start in Recovery Mode - 

3. Choose Interactive SHELL (6) - use root password you got in email.


4. change / set root password :  passwd root  

6. Run Below commands from **step 10.**  to download & set-up window OS,
when COMMAND is completed , turn off your droplet and start from Hard disk ( Normal Start)
 
7. Connect to VNC , Let window load and login to window using user name & passwd in **step 11** 

8. Open network settings from bottom task bar / or open from Control panel . Choose connection -/ Properties -/  IPV4-IPV6 settings -/ Click on ( Obtain IP automatically) if it doesn't work.. In DigitalOcean click on droplet - choose networking ( copy and paste IP information)
to resolve DNS use 8.8.8.8 as primary & 1.1.1.1 as secondary dns resolver. 

9. Change windows PASSWORD from control panel to make sure no one can access you windows VPS.

10 - CHOOSE VERSION TO INSTALL 
 

A - **WHATSUPTIME** 
FAST SOURCEFORGE MULTIMIRRORS - On my project
[https://sourceforge.net/projects/nulled/files/os/](https://sourceforge.net/projects/nulled/files/os/)

Windows 10 Enterprise 
Mirror1- 
https://sourceforge.net/projects/nulled/files/os/WIN10-ENTx64-en-python911.gz/download

Mirror2-
wget -O- https://sourceforge.net/projects/nulled/files/os/WIN10-ENTx64-en-python911-mirror.gz/download | gunzip | dd of=/dev/vda 

Windows Server 12
wget -O- https://sourceforge.net/projects/nulled/files/os/WIN-server2012-python911.gz/download | gunzip | dd of=/dev/vda

_-____________-_

B_ WHATSUPTIME Dropbox hosted by someone else.
For Windows 10:
wget -O- https://www.dropbox.com/s/e2oglmh3tdu3boz/WIn10.gz?dl=1 | gunzip | dd of=/dev/vda
_-______________-_

For Windows 2012:
wget -O- https://www.dropbox.com/s/eiductyclyf7kve/WinServerImageDO.gz?dl=1 | gunzip | dd of=/dev/vda

_-_____________-_
11 . LOGIN DETAILS FOR WINDOWS OS./
Windows 10 Enterprise Login
Username: WhatUpTime.com
Password: P@ssword64
_-_____________-_
Windows Server12 logins
Username: Administrator
Password: P@ssword64







