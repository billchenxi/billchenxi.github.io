---
layout: post
title: How to build your own jekyll site
subtitle: It works!
date:       2016-3-21
author:     "Bill"
header-img: ""
thumbnail: 
tags: [Jekyll, website]
categories: [Jekylle]
---

# Do you want a website?

You are in luck. I just made this website with Jekyll and it's amazing! 

BUT, let me tell you some drawbacks that Jekyll statistic web have. For my website, I used two types of files, html and markdown.
You probably are familiar with the html, it can do literally anything you want, but it hard to learn and some of the functions may not be covertable with jekyll engine and it's hard to learn.
On the other side markdown is easy to learn and use but it has so many limitations, just like this post. You can display content, but for multimedia it's a no. For example the youtube video below:  

[![All I ask](http://img.youtube.com/vi/utNKjspT39I/0.jpg)](https://www.youtube.com/watch?v=utNKjspT39I?autoplay=T "All I ask")

The only way you can kind of solve is wrapping the video link into a click-able picture. And the picture is the auto-generated picture from Youtube.

<pre><code>[![All I ask](http://img.youtube.com/vi/utNKjspT39I/0.jpg)](https://www.youtube.com/watch?v=utNKjspT39I?autoplay=T "All I ask")
</code></pre>

Similiar situation for music players like [SoundCloud](www.soundcloud.com), [Spodify](www.spodify.com) and [Google Player](www.google.com/play). And you cannot stream on your website unless is the html format. The home page of my site is using html file and it streams music from SoundCloud.

By now, if you still want to build your own statistic website, then you can follow the below tutorial. And for making my life easier, I will only demonstrate the procedure for Mac and Linux. For Windows is similar.

# 1. Install the Jekyll on your machine.
You can find all the information here: [Jekyll](http://jekyllrb.com). 

On mac, I believe ruby is already installed, so you can just simply run the following code, but on Windows, you might need to install ruby first.
<pre><code>~$ gem install jekyll
</code></pre>

Then you can test by generating a "website" at your home directory>
<pre><code>~$ jekyll new my-awesome-site # you can change to your name suits you
</code></pre>

To make your website alive, of course locally, you can do:
<pre><code> ~$ cd my-awesome-site       # change directory to the website folder you just created 
 ~/my-awesome-site $ jekyll serve
</code></pre>

Now open your browser and type http://localhost:4000 and see.

# 2. How to configure the all the files.
I understand there are so many 
