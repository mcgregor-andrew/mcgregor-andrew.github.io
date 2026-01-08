---
layout: single
title: "Publications"
permalink: /publications/
---

<ul class="pub-list">
{% assign pubs = site.publications | sort: "date" | reverse %}
{% for post in pubs %}
  {% include pub-item.html post=post %}
{% endfor %}
</ul>
