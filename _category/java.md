---
layout: category
tag: java
permalink: "/category/java"
---

{% for post in site.categories.java %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}