---
layout: page

permalink: /en
lang-ref: index
---

Kunststofferei is an open collective working locally on practical solutions to plastic waste in Leipzig as part of the Precious Plastic Universe.

# Latest News

Find our latest announcements here of and be sure to check out the [News](/news) section to see what we've been up to in the past.

<div class="tiles">
{% for post in site.posts  limit:8 %}
  {% if post.lang == page.lang and post.category != "team" %} 
	{% include post-grid.html %}
  {% endif %}
{% endfor %}
</div>

