---
layout: post
title:  "Blogging on Github Pages"
date:   2018-08-28 12:00:00 -0500
categories: code
---
This blog is completely [open source](https://github.com/tarunsachdeva/blog/). It is based on the [Jekyll](https://jekyllrb.com/) library, which helps people create static sites, and is hosted on [Github Pages](https://pages.github.com/). 

Why?

- Github let’s me track changes in an [extremely detailed](https://github.com/tarunsachdeva/blog/commits/gh-pages) way. All my edits are available for anyone to see, which creates a strange sense of vulnerability and accountability. 
- Hosting it myself allows a lot of control, with minimal overhead because it is a static site (there is no database). Jekyll has great integration with Github and an active community to help with any issues.

Everything here is boilerplate Jekyll. A few small modifications:


* ~~I've slightly [modified](https://github.com/jekyll/minima#customization) the default theme ([Minima](https://github.com/jekyll/minima)), and changes can be seen in commits in the ```_layouts```, ```_sass``` and ```_includes``` directories in the [repo](https://github.com/tarunsachdeva/blog/).~~
* The blog lives in a subdirectory based on instructions from [this article](http://shahrajat.com/2016-06-22-install-jekyll-subdirectory-blog-github-pages/)).
* I'm using draft posts in the way described by [this simple solution](https://gist.github.com/carlo/2870636) (drafts are enabled in Jekyll natively through the ```_drafts``` folder, but I like this solution bettter.)
* URL structure updated so it doesn't include categories (see ```permalink``` in [```_config.yml```](https://github.com/tarunsachdeva/blog/blob/gh-pages/_config.yml))
* Tags display will be added soon (I like [this approach](http://longqian.me/2017/02/09/github-jekyll-tag/)).

~~