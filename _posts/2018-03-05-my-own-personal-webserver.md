---
layout: post
title: Setting up a Personal Webserver
date: 2018-03-05
categories:
  - projects
description: I built a personal webserver for hosting my websites
image:
image-sm:
author: Devin Matte
author-image: https://devinmatte.me/images/devinmatte.jpg
author-bio: A Software Engineering Major with a love for Web Development
author-email: matted@csh.rit.edu
author-social:
  github: https://github.com/devinmatte
  linkedin: https://www.linkedin.com/in/devinmatte
  website: https://devinmatte.com
---

When someone makes a website, often the last thing they think about, is where to host it.
For me, it was no different.
I built a website for myself, and once I went to host it, I had to consider where made the most sense.
For a long time, I had it hosted using GitHub pages, and pointed both my domains to GitHub's server.
That worked in order to get my site online, however it came with a lot of drawbacks.
I couldn't use SSL for secure https.
I couldn't use subdomains effectively.
I couldn't run any backend/complex code.
It wasn't ideal, and after a while became frustrating.
So I decided it was time to host it myself.


In order to host it myself, I needed a server.
I set up a server running Ubuntu 16.04 LTS on DigitalOcean, and began learning how to use NGINX.
The main reasons that I wanted a webserver though, was to be able to use SSL and subdomains and NGINX allowed for that.
NGINX is a webserver that allows for routing and handling multiple domains, domains and setting headers of requests.


With having this personal webserver away from GitHub, the other advantages were clear.
The ability to use grunt or gulp, using sass, docker or write backend java, python, php, ect. 
