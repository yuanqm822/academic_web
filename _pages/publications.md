---
layout: single
title: "Publications"
permalink: /publications/
author_profile: true
---

{% assign author = site.author %}
{% if author.googlescholar %}
You can also find my articles on [my Google Scholar profile]({{ author.googlescholar }}).
{% endif %}

{% assign pubs = site.publications | sort: "date" | reverse %}
{% assign articles = pubs | where: "type", "article" %}
{% assign theses = pubs | where: "type", "thesis" %}

Journal articles
------

<ul class="publication-list">
{% for pub in articles %}{% include publication-item.html %}{% endfor %}
</ul>

Thesis
------

<ul class="publication-list">
{% for pub in theses %}{% include publication-item.html %}{% endfor %}
</ul>
