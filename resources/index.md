---
layout: archive
---

<div class="tiles">
{% for post in site.pages %}
	{% if post.categories == 'resources' %}
   	{% include post-grid.html %}
   {% endif %}
{% endfor %}
</div><!-- /.tiles -->