---
layout: page
title: "發表列表"
---

<ul>
  {% for pub in site.data.publications %}
    <li>
      <strong>{{ pub.title }}</strong><br>
      作者：{{ pub.authors }}<br>
      刊登於：{{ pub.journal }} ({{ pub.year }})<br>
      <a href="{{ pub.url }}">閱讀全文</a>
    </li>
  {% endfor %}
</ul>