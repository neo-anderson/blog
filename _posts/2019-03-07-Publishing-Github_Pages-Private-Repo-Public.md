---
layout: post
current: post
cover:  assets/images/welcome.jpg
navigation: True
title: Publishing Github Pages After Making Private Repo Public 
date: 2019-03-07 22:08:00
tags: [github, tutorial, blog, dev, troubleshooting]
class: post-template
subclass: 'post tag-getting-started'
author: aswin
---

# Publishing Github Pages After Making Private Repo Public

Publishing Github Pages from private repositories is a Github Pro feature at the time of writing this blog post. See https://help.github.com/articles/github-s-billing-plans/#billing-plans-for-personal-accounts . If you turn the repository private, your Github Pages site/blog will not be accessible if you are using GitHub Free.

However, if you set your private repository public again, your Github Pages site/blog will not published automatically. To publish your site/blog again, follow these steps:

1. Make the repository public again in the settings.
2. Push a new commit. A new commit should be pushed before your site will be built and served again.
3. Grab a coffee and wait while your site finishes building and is propagated across GitHub's CDN. In my case, the site was back up and running within a minute. GitHub CSE told me it may take 10-20 minutes sometimes.
4. Access your GitHub Pages site/blog.

If this doesn't work, contact GitHub Support.
