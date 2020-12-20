---
layout: post
title: Symfonos 3 Vulnhub Walkthrough
subtitle: 
tags: [oscp, vulnhub]
---

## Enumeration

After digging out of the rabbit hole, I tried to fuzz the `/cgi-bin` directory. 
This proved to be the right move as we discovered a file at `/cgi-bin/underworld`. 

![snip]({{ "/images/cgi_bin_dir.png" | absolute_url }})