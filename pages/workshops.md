---
title: Workshops
layout: page-fullwidth
permalink: /workshops/
header:
  image_fullwidth: "generic-gradient.png"
---

Accepted workshops will be announced here.

{% if site.data.workshops.size > 0 %}
<h2>Accepted Workshops</h2>
<ul>
{% for workshop in site.data.workshops %}
    <li>
    <b>
        {% if workshop.acronym %}
            {{- workshop.acronym -}}:
        {%- endif -%}
        {{- workshop.name -}}
    </b>
    {%- if workshop.url -%}
    , <a href="{{ workshop.url }}">Website</a>
    {%- endif -%}
    <br>
    <i>
    {%- for organizer in workshop.organizers -%}
        {{- organizer -}}
        {%- if forloop.last == true -%}
            .
        {%- else -%}
            ,&nbsp;
        {%- endif -%}
    {%- endfor -%}
    </i>
    </li>
{% endfor %}
</ul>
{% endif %}

If you have any questions, please get in touch with our [workshop chairs]({{ site.baseurl }}/organization/).
