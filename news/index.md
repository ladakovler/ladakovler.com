---
layout: home
title: "News & Blog"
permalink: /news/
author_profile: false
excerpt: "Latest news and updates from Lada Kovler"
header:
  overlay_image: /assets/images/news-header.jpg
  overlay_filter: rgba(0, 0, 0, 0.6)
  caption: "News"
---

## Latest News

{% for post in site.posts %}
  <div class="news-item">
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <small class="post-date">{{ post.date | date: "%B %d, %Y" }}</small>
    <p>{{ post.excerpt }}</p>
    <a href="{{ post.url }}" class="btn btn--primary">Read More</a>
  </div>
{% endfor %}

*Last updated: July 16, 2024*
