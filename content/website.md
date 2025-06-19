---
title: "website"
date: 2025-06-05
draft: false
---

This website runs on an `nginx` server, which is in turn hosted on a VPS somewhere in the US. This website is built using Hugo, a static site generator which uses markdown and go/html to generate light-weight pages.

This site used to run on Dokuwiki. Before Dokuwiki, it used Wordpress, and also Bludit.

I used Bludit in the early days because my [brother](https://keyaar.in) used Bludit. Then I had some trouble with Bludit and I figured I would use Wordpress, because it gave me a login page to access the site and create new pages—which meant I could write stuff and post it on the go. But behind the scene it offered me too many things and I found it too eager to be of use to me. DokuWiki was good. I could install a blog plugin and turn it into a blog; it gave me a login page and an editor window. But then it used some quirky markdown which meant I could not use a simple octothorpe (ahem) to define a heading. I also tried using jekyll for a while, but I could not get it to deployment, and the ruby+gems thing was too convoluted to figure out at that time.

Then I had a eureka moment and the 'model' of computing just clicked in my brain. With a lot of help from reddit and chatgpt, I rented a VPS, installed nginx on it, and learned the basics of hugo. I downloaded a theme, edited it so much that it broke, deleted it, and made my own theme. I figured out a way to write stuff locally on my machine, thus lowering the writing barrier, and pushing the site to the VPS while versioning it with git.

While I would like to play around with site-building frameworks, right now I focus on building my skills on go/html templating.
