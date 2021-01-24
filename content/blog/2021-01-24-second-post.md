---
path: lorem
date: 2021-01-24T17:01:36.138Z
title: second post
image: /img/screenshot_2.png
---
This is the basic function of Netlify CMS - providing a comfortable editing experience and outputting raw content files to a Git repository. You’ve probably noticed that, even though the file was created in your repo, it’s not anywhere on your site. That’s because Netlify CMS doesn’t go beyond creating the raw content - it’s able to work with almost any static site generator because it allows the generator to determine how to build the raw content into something useful, whether for a website, mobile app, or something else entirely.

![](/img/screenshot_2.png)

![](/img/screenshot_5.png)

Right now, Gatsby doesn’t know the new blog post is there, and it isn’t set up to process Markdown. Let’s fix that.