---
layout: default
title: "Home"
---

# Welcome to the NOCTURN Automation Blog

This is the home page for the NOCTURN Automation Blog. We share updates on:
- Museum informatics
- Imaging technology
- Raspberry Pi projects for automated metadata

---

## Recent Posts

{% if site.posts.size > 0 %}
<ul>
  {% for post in site.posts limit:5 %}
    <li>
      <strong><a href="{{ post.url | relative_url }}">{{ post.title }}</a></strong>  
      <br>
      <small>{{ post.date | date: "%b %d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>

[See all posts]({{ '/archives' | relative_url }})
{% else %}
<p>No blog posts yet. Stay tuned!</p>
{% endif %}

---

## About Us

Learn more about our initiative on the [About page]({{ '/about/' | relative_url }}).

