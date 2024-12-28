---
layout: default
title: "Home"
---

# Welcome to the NOCTURN Automation Blog

This is the home page for the **NOCTURN Automation Blog**. We share updates on:

- [Using Raspberry Pi devices to parse Metadata from X-ray machines](https://github.com/johntrue15/NOCTURN-X-ray-repo)
- [Creating GitHub branches for X-ray facilities to store their metadata with releases](https://github.com/johntrue15/NOCTURN-X-ray-repo/tree/main/agent)
- [Utilizing metadata through GitHub Actions to connect with external sources](https://github.com/johntrue15/NOCTURN-X-ray-repo/tree/main/.github)
- - [Configuring Cursor to indefinitely maintain and upgrade this codebase and blog](https://github.com/johntrue15/NOCTURN-X-ray-repo/tree/main/.github/cursor)


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

