---
layout: default
---

{% for category in site.categories %} 
<h2><a href="{{ category.url }}">{{ category.title }}</a></h2>
<p>{{ category.slug }}</p>
{% endfor %}
