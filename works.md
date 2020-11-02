---
title: WEBサイト
---
## WEBサイト作品集
<ul>
  {% for post in site.posts %}
    {% if post.tag == "web" %}
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
        <p>{{ post.description }}</p>
        <p>{{ post.date }}</p>
      </li>
    {% endif %}
  {% endfor %}
</ul>