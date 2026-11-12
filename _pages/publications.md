---
layout: single
title: "Publications"
permalink: /publications/
author_profile: true
---

{% assign author = site.author %}
{% assign all = site.publications | sort: "date" | reverse %}
{% assign pubs = all | where: "type", "article" %}
{% assign theses = all | where: "type", "thesis" %}

<p class="lead">{{ pubs | size }} peer-reviewed articles on speech motor control, bilingual language control and the cerebellum.{% if author.googlescholar %} Also on <a href="{{ author.googlescholar }}">Google Scholar</a>.{% endif %}</p>

Journal articles
------

<p class="note">† Joint first authors.</p>

{% include publication-years.html %}

Thesis
------

{% assign pubs = theses %}
{% include publication-years.html %}
