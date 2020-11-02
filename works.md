---
title: WEBサイト
---
## WEBサイト作品集
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <p>{{ post.date }}</p>
    </li>
  {% endfor %}
</ul>