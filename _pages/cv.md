---
layout: single
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

Current position
------

**Computational Technical Expert**<br>
Centre for Integrative Neuroscience and Neurodynamics (CINN), University of Reading

Education
------

* **DPhil in Experimental Psychology**, University of Oxford (St John's College)
  * Thesis: *The corticocerebellar network in speech adaptation: evidence from non-invasive brain stimulation and brain imaging*
  * Supervisors: Prof. Kate Watkins and Prof. Heidi Johansen-Berg
  * Based at the Oxford Centre for Integrative Neuroimaging (OxCIN)
* **MSc in Psychology**, State Key Laboratory of Cognitive Neuroscience and Learning, Beijing Normal University
* **BSc**, Northeast Normal University

Awards and scholarships
------

* Clarendon Scholarship, Clarendon Fund and St John's College, University of Oxford
* North Senior Scholarship, St John's College, University of Oxford
* British Neuroscience Association (BNA) Scholars Programme

Research methods
------

* Structural and functional MRI
* Non-invasive brain stimulation
* EEG
* Altered auditory feedback and speech acoustics

Publications
------

{% assign pubs = site.publications | sort: "date" | reverse %}
<ul class="publication-list">
{% for pub in pubs %}{% include publication-item.html %}{% endfor %}
</ul>
