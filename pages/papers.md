---
title: Accepted Papers
layout: page-fullwidth
permalink: /papers/
header:
  image_fullwidth: "generic-gradient.png"
---

Accepted papers will be announced here.

{% if site.data.papers.size > 0 %}
## Archival Papers

<ul>
{% for paper in site.data.papers %}
    {% if paper['archival_status'] != "" and paper['archival_status'] != "Non-Archival" %}
        {% include paper.html p=paper %}
    {% endif %}
{% endfor %}
</ul>

## Non-Archival Papers

<ul>
{% for paper in site.data.papers %}
    {% if paper['archival_status'] == "" or paper['archival_status'] == "Non-Archival" %}
        {% include paper.html p=paper %}
    {% endif %}
{% endfor %}
</ul>
{% endif %}
