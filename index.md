---
layout: default
title: Packet Stories
---

Welcome to Packet Stories. I am Savan Patel, a network analyst sharing details about what I learned. This site holds configuration examples, troubleshooting notes, lab write-ups, and short stories from real networking projects.

Below you'll find the latest posts. Click any post title to read the full article.

<ul>
{% for post in site.posts %}
<li>
<a href="{{ post.url }}">{{ post.title }}</a> — <small>{{ post.date | date: "%b %-d, %Y" }}</small>
</li>
{% endfor %}
</ul>
