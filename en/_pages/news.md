---
layout: page
title: News

permalink: /en/news/
lang-ref: news
---

<div class="tiles">
{% for post in site.posts %}
  {% if post.lang == page.lang and post.category != "team" %} 
	{% include post-grid.html %}
  {% endif %}
{% endfor %}
</div>
