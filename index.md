---
layout: default
---
{% for page in site.posts limit:5 %}
{% assign body = page.content %}
{% include post.html %}
{% endfor %}