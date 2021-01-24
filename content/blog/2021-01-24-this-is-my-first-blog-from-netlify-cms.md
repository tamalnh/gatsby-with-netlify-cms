---
path: first-post
date: 2021-01-24T16:24:29.726Z
title: This is my first blog from netlify cms
---


Alright - you’re all set to make changes in Netlify CMS and see them as commits in your GitHub repo! Open Netlify CMS on your deployed site at `/admin/`, allow access to GitHub when the permissions window pops up (check for blocked pop ups if you don’t see it), and try creating and publishing a new blog post. Once you’ve done that, you’ll find a new “blog” directory in your GitHub repo containing a Markdown file with your blog post content!

This is the basic function of Netlify CMS - providing a comfortable editing experience and outputting raw content files to a Git repository. You’ve probably noticed that, even though the file was created in your repo, it’s not anywhere on your site. That’s because Netlify CMS doesn’t go beyond creating the raw content - it’s able to work with almost any static site generator because it allows the generator to determine how to build the raw content into something useful, whether for a website, mobile app, or something else entirely.

Right now, Gatsby doesn’t know the new blog post is there, and it isn’t set up to process Markdown. Let’s fix that.