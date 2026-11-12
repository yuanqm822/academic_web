---
permalink: /
title: "About"
excerpt: "Speech and language neuroscientist at the University of Reading"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<p class="lead">I'm a Computational Technical Expert at the <a href="https://research.reading.ac.uk/cinn/">Centre for Integrative Neuroscience and Neurodynamics (CINN)</a>, University of Reading, where I support the computational and methodological work behind the centre's neuroimaging and brain stimulation research.</p>

I completed my PhD in Experimental Psychology at the University of Oxford as a Clarendon Scholar, with a thesis on the sensorimotor control of speech, supervised by Prof. Kate Watkins and Prof. Heidi Johansen-Berg. My research was based at the Oxford Centre for Integrative Neuroimaging (OxCIN). Before Oxford, I took an MSc in Psychology at the State Key Laboratory of Cognitive Neuroscience and Learning, Beijing Normal University and a BSc at Northeast Normal University.

Alongside my role, I'm a speech and language neuroscientist. My research uses MRI to investigate how brain function and structure differ in people with speech and language disorders, and non-invasive brain stimulation to modulate and enhance speech production. I also study language production in bilinguals using MRI and brain stimulation, and collaborate on work examining the cerebellum's role in speech and reading.

Recent publications
------

{% assign pubs = site.publications | sort: "date" | reverse %}
<ul class="pub-list">
{% for pub in pubs limit: 3 %}{% include publication-item.html %}{% endfor %}
</ul>

<a class="more" href="{{ '/publications/' | relative_url }}">All publications</a>
