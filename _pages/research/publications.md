---
title: "Publications"
layout: archive
permalink: /research/publications/
toc: true
---

## Peer-Reviewed Papers
{% for paper in site.data.publications %}
- **{{ paper.title }}**  
  *{{ paper.journal }}*, {{ paper.year }}.  
  [DOI]({{ paper.doi }}) | [PDF](/assets/pdfs/{{ paper.pdf }})  
{% endfor %}