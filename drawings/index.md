---
layout: page
title: Drawings
excerpt: "An archive of the different drawing categories."
---

<ul class="post-list">
{% for post in site.categories.articles %}
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <!-- <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span> -->
  </a></article></li>
{% endfor %}
</ul>
