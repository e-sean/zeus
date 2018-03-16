---
title: Quickbox - A unique way to manage your server
date: 2018-03-17
categories:
- linux
tags:
 - linux
 - server
 - quickbox
 - plex
 - torrent
metaAlignment: center
keywords:
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

Probably the best attribute of linux, beside being free, is the community. Thousands of people all over the world pour their heart and soul to build spectacular applications on this platform. <!--more-->


This is people all over the world are shifting more towards open source operating systems and softwares. With Linux, the possibilities are endless. And I found another such gem the other day. 

**Quickbox**

Quickbox is more than just a script, as they say it. It allows you to install many useful applications with just a click and gives you relevant data in a beautiful format. Now, I like to install everything myself rather than relying on scripts and frankly that's how one learns about the linux environment. But there are times when certain tasks can be done with scripts only. Honestly scripts are both good and bad. They save your time but also are difficult to manage. 

So Quickbox, as I was saying, makes your life a little easier. First of all look at the interface - 

![Quickbox](/images/quickbox/1.png)

It is so great to look at. But quickbox is more than just a fancy front end. It has more than 20 applications built in like Plex, Plexpy, Deluge, Resilio Sync, Nextcloud and many more. Click install and done. I am using Quickbox for more than 3 days now and I am quite impressed. Although there are a few issues here and there, but the community and the developers are very helpful. One might stumble here and there, at first, then one gets a hang of it. 

## How to install it?

```
apt-get -yqq update; apt-get -yqq upgrade; apt-get -yqq install git lsb-release; 

git clone https://github.com/QuickBox/QB /etc/QuickBox

bash /etc/QuickBox/setup/quickbox-setup
```

That's all. The script will let you know what to do next. 