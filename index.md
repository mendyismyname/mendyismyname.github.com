---
layout: page
title: MendyIsMyName
tagline: My new bog
---

    
## Sample Post

This Blog is being created using Jekll and is Github


    sample code here

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



