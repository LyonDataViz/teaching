---
layout: default
---

## Gallerie des projets

[In english](./index.html)

{% assign projects = "1,2,3,4,5,6,7,8,9,10,11,12,13,15,16" | split: "," %}

{% for i in projects %}
  {% assign description-fr = i | append: "-desc-fr.md" %}
  {% if i == "9" %}
    {% assign image = i | append: "-thumbnail.gif" %}
  {% else %}
    {% assign image = i | append: "-thumbnail.png" %}
  {% endif %}
  {% include_relative {{description-fr}} %}
  ![]({{image}})
{% endfor %}
