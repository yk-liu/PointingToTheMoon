---
title: Build Your Blog with GitHub Pages
tags: Jekyll
categories: Jekyll
mathjax: true
description: Build Your Blog with GitHub Pages
---

This page's comment is enabled, scroll down to see.

# Why GitHub Pages?

1. It's simple.
   1. The Domain is just `username.github.io`. You don't need to buy your own domain. PS, All domains must be registered by the owner with ID. So that saves you a ton of trouble. But GitHub pages also allows you to 
   2. GitHub pages build the website for you. This means you don't need to install `jekyll` or `ruby`, you don't need you locally build your website and publish it. You just commit your source code and that's all. 
   3. After properly configured, you can write in `markdown`, and `push` (a fancy name for upload) to GitHub.  Things like equations, lists, tables, mermaid-diagrams, images, or videos are automated supported. This means all you'll need is a text editor as simple as good old notepad.exe to write your post, yet I strongly recommend [`typora`](https://www.typora.io/). As the time of writing, it is free.

2. You have absolute control over anything.

   1. The look. WordPress, blogspace as well as other services does provide good-looking templates. But some of them have unnecessary constrains of where to put what. While on GitHub, you get to control what your pages look like. Still, there are thousands of readily made themes at your disposal if you are lazy. With a few modifications, you can tailor your website the way you want.
   2. Functions. RSS feed, search, table of contents, pagination, visitor analysis, commenting, *etc*. anything you can think of it out there. GitHub is a static site generator, which means there are no server side calculations. But you can always trick the users with a few walk-arounds and CDNs.

3. There is a nice touch. GitHub's famous for being used by techies.

   Having your own website built entirely by yourself.

4. Limitations

   GitHub Pages source repositories have a recommended limit of 1GB. Published GitHub Pages sites may be no larger than 1 GB. GitHub Pages sites have a soft bandwidth limit of 100GB per month.	GitHub Pages sites have a soft limit of 10 builds per hour. See [here](https://help.github.com/articles/what-is-github-pages/#usage-limits)
	
	 
# How do I start?

Download this repo, and add it to your GitHub Desktop as local repo. CHange the name of the repo to your-username.github.io, and you are all set.

## About Git

I am going to assume that you know the basic operations of git. If not, just download the [GitHub Desktop](https://desktop.github.com/), and do everything in GUI. For the most of bloggers, only commit and push is required. For you to publish your work, save your file in your editor, go to GitHub Desktop, commit your changes, and push.

<img src="" width="80%">

## What Should I Modify

Here is a list of files you need to modify

1. License.md: add your name.

2. Readme.md: add your description.

3. config.yaml: add your username, GitHub-links etc. 

After that, you should be able to enjoy your blogging!


