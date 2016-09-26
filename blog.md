---
layout: page
title: Blog
permalink: /blog/
---

I am a  ['good procrastinator'](http://paulgraham.com/procrastination.html), and hence blogs irregularly. Most of my blog entries involve something around robots, computer vision or programming. I am currently porting my [old blog](http://achuwilson.wordpress.com/blog) and all entries are not updated. It will be done as time permits.

<ul class="listing">
{% for post in site.posts %}
  {% capture y %}{{post.date | date:"%Y"}}{% endcapture %}
  {% if year != y %}
    {% assign year = y %}
    <li class="listing-seperator">{{ y }}</li>
  {% endif %}
  <li class="listing-item">
    <time datetime="{{ post.date | date:"%Y-%m-%d" }}">{{ post.date | date:"%Y-%m-%d" }}</time>
    <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>


