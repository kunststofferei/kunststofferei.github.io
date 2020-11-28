---
layout: page

permalink: /de
lang-ref: index
---

Kunststofferei ist eine ...

# Aktuellste Neuigkeiten

Find our latest announcements here of and be sure to check out the [News](/news) section to see what we've been up to in the past.

<div class="tiles">
{% for post in site.posts limit:8 %}
  {% if post.lang == page.lang and post.category != "team" %} 
	{% include post-grid.html %}
  {% endif %}
{% endfor %}
</div>

