---
title: "Blog Creation"
date: 2024-08-18T10:41:55-04:00
draft: true
toc: false
images:
tags:
  - untagged
---

# Starting a Blog
I’ve been looking to start a blog for a few months, but I’ve spent most of that time puttering about without actually doing anything. I've spent altogether too  many hours looking at Drupal vs Wordpress, looking into hosting options, reading documentation and articles. What finally pushed me over the edge was an article I read on a blog written using it. It looked nice, even on mobile, and the way the author talked about it made it sound reasonably painless to set up. As a static site generator, it would work with free CDN options like Github Pages. It being open source, and written in Go, a language I’m interesting in learning, also both contributed to my choice. It also had an easy seeming quickstart guide. I was thinking I could be done within a day.

## Themes. - [not sure where to put this]
I want minimalism, a good mobile experience, and an easily implementable dark mode.
Hermit v2 seems ok, but I'm currently sticking with friend-ng, given that I found a blog using it that seems to do everything I would want.

## Issues
Unfortunately, problems arose, as they nearly always do. After the fact I found this article [https://yawpitchroll.com/posts/hugo-probably-is-not-for-you/] I didn’t have nearly the same issues with themes that he did. My theme was out of date, but the error messaging on what was deprecated and what to replace it with was straightforward enough that I could do it without any real understanding of Go. The lack of signaling where the errors were coming from was a bit annoying, but grep saved the day and that was the end of my struggle with themes. No, my real issue was entirely my fault.
I have major gaps in my understanding of how git works. 
I eventually tossed my hands up and followed this blog post https://blog.hellohuigong.com/en/posts/how-to-build-personal-blog-with-github-pages-and-hugo/ on how to setup two repositories, one of which stores your source code, the other of which github actions compile the actual website to.

