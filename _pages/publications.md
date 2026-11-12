---
layout: single
title: "Publications"
permalink: /publications/
author_profile: true
---

{% assign all = site.publications | sort: "date" | reverse %}
{% assign pubs = all | where: "type", "article" %}
{% assign theses = all | where: "type", "thesis" %}

Journal articles
------

<p class="note">† Joint first authors.</p>

{% include publication-years.html %}

Thesis
------

{% assign pubs = theses %}
{% include publication-years.html %}
