---
layout: blog
---

<ul>
{% for post in site.posts %}
<li>{{post.title}}</li>
{% endfor %}
</ul>
