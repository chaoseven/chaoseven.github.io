---
layout: default
---
{% for category in site.categories %}
<h3>{{ category[0] }}</h3>
{% for post in category[1] %}
<a href="{{post.url}}">{{ post.title }}</a>
{% endfor %}
{% endfor %}
