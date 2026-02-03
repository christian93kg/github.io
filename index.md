---
layout: default
title: "My Pentesting Blog"
---

# Welcome to My Pentesting Blog

OSCP Journey and HTB Writeups

---

{% for post in site.posts %}
  <div>
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <p><small>{{ post.date | date: "%B %d, %Y" }}</small></p>
    <p>{{ post.excerpt }}</p>
    <hr>
  </div>
{% endfor %}
