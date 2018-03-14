---
title: Running Hugo server on multiple devices
date: 2018-03-14
tags:
 - linux
 - hugo
metaAlignment: center
---

When you run Hugo server it only binds to the localhost of the machine your are running on. Let's say you want to view your current website on multiple device in your network. By visiting your computer's IP address, it should work. Sadly, for me it didn't. So I digged the web looking for possible solutions and found this one. 

THe usual way of running Hugo server is by giving the following command

```
hugo server -w
```

Instead bind it to your computer's IP like this

```
hugo server --bind=10.0.0.5 --baseURL=http://10.0.0.5:1313
```

10.0.0.5 is my computer's IP address. Make sure you open 1313 port in firewall as well.
It's a nifty litle solution and work flawlessly. 
Now you can view your live site on every device inside your LAN. 