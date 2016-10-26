---
layout: default
maintitle: Aquent Gymnasium Press Releases
permalink:
baseurl: /pr/
---

{% for post in site.posts %}
<dl>
    <dt>{{ post.date | date: "%B %e, %Y" }}</dt>
    <dd><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></dd>
</dl>
{% endfor %}
