---
title: WEBサイト
---
## WEBサイト作品集
{{ site.time | date_to_string }}
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <p>{{ post.date }}</p>
    </li>
  {% endfor %}
</ul>