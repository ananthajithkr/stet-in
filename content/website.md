---
title: "website"
date: 2025-06-05
draft: false
---

This website runs on an `nginx` server, which is in turn hosted on a VPS somewhere in the US. This website is built using Hugo, a static site generator which uses markdown and go/html to generate light-weight pages.

Hugo builds the site on my local machine to a folder and syncthing syncs the folder and its contents to my VPS. The source of truth is my local machine.

This site used to run on Dokuwiki. Before Dokuwiki, it used Wordpress, and also Bludit.

I used Bludit in the early days because my [brother](https://keyaar.in) used Bludit. Then I had some trouble with Bludit and I figured I would use Wordpress, because it gave me a login page to access the site and create new pages—which meant I could write stuff and post it on the go. But behind the scene it offered me too many things and I found it too eager to be of use to me. DokuWiki was good. I could install a blog plugin and turn it into a blog; it gave me a login page and an editor window. But then it used some quirky markdown which meant I could not use a simple octothorpe (ahem) to define a heading. I also tried using jekyll for a while, but I could not get it to deployment, and the ruby+gems thing was too convoluted to figure out at that time.
