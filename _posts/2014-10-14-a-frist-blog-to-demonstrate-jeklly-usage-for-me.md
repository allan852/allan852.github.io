---
layout: post
title: "A Frist Blog To Demonstrate Jekyll Usage For Me"
description: ""
category: 
tags: [Jekyll]
---
{% include JB/setup %}
[Jekyll](http://jekyllrb.com/) is a simple, blog-aware, static site generator. 
It takes a template directory containing raw text files in various formats, 
runs it through Markdown (or Textile) and Liquid converters, and spits out 
a complete, ready-to-publish static website suitable for serving with your 
favorite web server. 

[Jekyll-Bootstrap](http://jekyllbootstrap.com/) is a full blog scaffold for Jekyll based blogs. The quickest 
way to blog on GitHub Pages.

### Write a Post
reate posts easily via rake task:
{% highlight python %}
$ rake post title="Hello World"
{% endhighlight %}

### Deploy to GitHub
After you've added posts or made changes to your theme or other files, simply commit them to your git repo and push the commits up to GitHub.
{% highlight python %}
$ git add .
$ git commit -m "Add new content"
$ git push origin master
{% endhighlight %}

