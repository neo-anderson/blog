---
layout: post
current: post
cover:  assets/images/welcome.jpg
navigation: True
title: Easiest way to create a Jekyll blog
date: 2018-05-07 14:01:00
tags: [getting started, tutorial]
class: post-template
subclass: 'post tag-getting-started'
author: aswin
---

# Easiest way to create a Jekyll blog.

1. **Pick a theme** that you like on github.
- [Jekyll Now](https://github.com/barryclark/jekyll-now), [Demo](http://www.jekyllnow.com/).
- [Poole](https://github.com/poole/poole), [Demo](http://demo.getpoole.com/).
- [Hyde](https://github.com/poole/hyde), [Demo](http://hyde.getpoole.com/).
- [Lanyon](https://github.com/poole/lanyon), [Demo](http://lanyon.getpoole.com/).
- [Left](https://github.com/holman/left), [Demo](http://zachholman.com/posts/left).
- [Skinny Bones](https://github.com/mmistakes/skinny-bones-jekyll), [Demo](https://mmistakes.github.io/skinny-bones-jekyll/)
... and a lot more!
I chose [Jasper2](https://github.com/jekyller/jasper2).
2. **Fork** the repository by clicking the fork button on the top right. You can give it a name of your choice or keep the original name. If you want the blog to be available at yourgithubusername.github.io, name your repo `yourgithubusername.github.io` and follow this [Quick Start guide](https://github.com/barryclark/jekyll-now). If you want the blog at a url path like yourgithubusername.github.io/blog/ or similar, name your repo based on the path following the domain (`blog` in this example) and follow the rest of the steps.
3. In the forked repository, open `_config.yml` and click **Edit**
4. **Edit the baseurl** to match your repository's name. For example, `baseurl: "/blog/"`. Do **NOT** forget the slashes. You can edit the rest of the details later.
5. **Commit** the change by clicking the button at the bottom.
6. Clicking **Settings** tab and scroll down to **Github Pages** section. Under **Source**, select **Master** branch and click **Save**.
7. Congrats! Your blog should be online at yourgithubusername.github.io/blog/ or whatever path you chose in step 2. You can change this path by modifying the repository name and editing the `_config.yml`.

The source for this blog is at [https://github.com/neo-anderson/blog](https://github.com/neo-anderson/blog) and I forked the base from [https://github.com/jekyller/jasper2](https://github.com/jekyller/jasper2)

# Next Steps
1. Add CNAME files and configure custom domain. Eg: asw.in/blog/
2. Go through the source files and config files and personalize the blog according to your needs. 
3. Add SEO plugin https://github.com/jekyll/jekyll-seo-tag
4. Use Google Webmasters tool to add properties - Eg: http://domain.com/blog/, https://domain.com/blog/, http://www.domain.com/blog/, https://www.domain.com/blog/
5. In the Webmasters tool, set the preferred domain to `domain.com`, instead of `www.domain.com` because the former looks cooler!
6. Submit the blog to other search engines.
7. Cross post to Medium (don't forget to add canonical link), steemit/busy (no canonical link feature unfortunately) and others.

# Resources
- [Why Jekyll? Read this story](https://intersect.whitefusion.io/open-web/goodbye-medium-hello-jekyll)
- [Two Blogs with the same domain](https://stackoverflow.com/questions/31914048/how-to-set-up-two-jekyll-blogs-on-github-pages-with-the-same-domain-cname)
> The simplest ways to manage custom domain on ghp is to set a CNAME (pointing to example.com) on username.github.io and any project repository hosting a gh-pages branch can be naturally reached at example.com/repositoryName
