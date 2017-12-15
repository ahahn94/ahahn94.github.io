---
layout: page
title: "Alle Posts"
published: true
permalink: blogposts.html
---
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
