---
title: Switching from Jekyll+Github to Hugo+Netlify
date: 2018-03-14
tags:
 - jekyll
 - hugo
 - github
 - netlify
metaAlignment: center
---

The only bad habit of mine is that I cannot sit doing nothing. I constantly need something to work on otherwise the grey matter inside my brain will turn to black. 
<!--more-->


So a couple of days back I was writing a new article for this blog and it was a daunting task. I used Jekyll as my static generator, *used*.
Jekyl became unavoidingly slow. It took nearly a minute to rebuild my site even when I changed a punctuation error. Those were some dark days of my life. And so I researched for alternatives and found a new static generator called **Hugo**.

**Hugo**, as they advertise, is really the fastest static generator. It took nearly 30ms to build my website everytime I make a change. 
**Hugo** is built with **Golang** which is way faster than **Ruby**. P.S. 60 sec vs 30ms, you be the judge. 
Running **Hugo** on Netlify is satisfyingly great. Did I mention that everything is free? I just pay yearly for my domain. That's all .


Second change that I made is change my hosting site. back then i used to host on GitHub, which by the way was more painful than installing *Arch linux*. Anyways, now I use Netlify. Netlify actually makes it easy to host static site. All I do is push changes in my git repo and Netlify builds my website on their server. Easy peasy. 


Here's how I did it:

- Create a new GitHub repository with my site's source code in it. 
- Create a Netlify account.
- Connect GitHub to Netlify.
- Click deploy.
- Done. Website is live!
- Also added a few DNS changes and custom domain in Netlify.


Netlify also manages you DNS entries which I haven't tried out yet. Primarily because I use Clouflare and I see no reason to switch my DNS provider. 

I'll let the minions express how I feel about my current setup:

![Minions](https://78.media.tumblr.com/tumblr_m0stlkPj4c1rrdywqo1_500.gif)
VIA GIPHY

