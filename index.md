---
layout: home
---

<style>ul{list-style:none; padding-left: 0px;}</style>

Testing


{% for post in site.posts %}
  * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ post.url }})
{% endfor %}
