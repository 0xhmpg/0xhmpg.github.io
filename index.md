---
layout: home
---

<style>ul{list-style:none; padding-left: 0px;}</style>

<ul class="posts">

  {% for post in site.posts %}
    <li><a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a> <small>— <time datetime="{{ post.date | date_to_string }}" itemprop="datePublished">{{ post.date | date_to_string }}</time></small></li>
  {% endfor %}
    
</ul>
