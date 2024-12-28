---
layout: default
title: "Archives"
permalink: /archives/
---

# Post Archives

{% if site.posts.size > 0 %}
<ul>
  {% for post in site.posts %}
    <li>
      <strong><a href="{{ post.url | relative_url }}">{{ post.title }}</a></strong><br>
      <small>{{ post.date | date: "%B %d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>
{% else %}
<p>No posts yet. Stay tuned!</p>
{% endif %}
