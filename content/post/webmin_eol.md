---
title: Webmin Panel Script and EOL
date: 2018-04-02
categories:
- linux
tags:
 - linux
 - server
 - webmin
metaAlignment: center
keywords:
- administration
- tech
- learn
- linux
- ubuntu
- server
- media
- technology
- ishan
- badgainya

---

A quick script to install Webmin panel. Only works in Ubuntu distribution. Script is written in Bash. <!--more-->


This script has been sitting on my desktop since months and I actually never uploaded this on GitHub. I was searching through my linux folder, which is a mess by the way, and found this script lying around. So I quickly made a new repo and uploaded on GitHub. 

Scripts are real time savers, if made the right way.

**Installation**

A more detailed guide about manually installing webmin can be found here - Post

To use this script just run the following two commands. 
Make sure you have **wget** installed. 


```
wget https://raw.githubusercontent.com/e-sean/webmin/master/webmin.sh 
sudo bash webmin.sh
```

**About EOL and line endings**

EOL = End of Line

If you are a dual boot user you will get this error at some point. While transferring text files between DOS systems and Unix/Linux systems, the end of line syntax also changes. 
While uploading this script to GitHub from Windows and the trying to run it, I got a bunch of errors. All of these error were related to these line of endings. A quick look at stackoverflow and some other forums solved my problem!

> Text files created on DOS/Windows machines have different line endings than files created on Unix/Linux. DOS uses carriage return and line feed ("\r\n") as a line ending, which Unix uses just line feed ("\n"). You need to be careful about transferring files between Windows machines and Unix machines to make sure the line endings are translated properly.

_Source: University of Toronto_

Notepad++ has a feature for EOL conversion built inside, given that you use Notepad++. 
