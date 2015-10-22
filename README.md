# opentracker-auto-installer

![](http://www.upimg.fr/ih/23yp.png)

This is a bash script that will allow anyone to install OpenTracker (BitTorrent) on their linux machine. Easy and automated script allowing user to choose settings before installation.

This script was originaly created by YIFY team on Google Code but no longer updated since 2012.

### Installation instruction

> Note : you need admin access to install the script.

First, we clone the git :
``` 
git clone https://github.com/XelionXS/opentracker-auto-installer 
cd opentracker-auto-installer
```
 
Then we make the script executable :
```
[sudo] chown [user] opentracker-auto-installer.sh
[sudo] chmod 755 opentracker-auto-installer.sh 
```

Launch the script :
```
[sudo] ./opentracker-auto-installer.sh
```
  
Follow all the script steps and when it's done :
```
Your announce URL :
http://[IP]:[PORT]/announce or udp://[IP]:[PORT]/announce

Your stats URL :
http://[IP]:[PORT]/stats
```

[Program website](http://erdgeist.org/arts/software/opentracker/)

[Original code from Google Code](https://code.google.com/p/opentracker-auto-installer/)
