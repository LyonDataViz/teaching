---
layout: default
---

## Gallerie des projets

[In english](./index.html)

{% assign projects = "1,2,3,4,6,9,10,11,12,13,14,15" | split: "," %}

{% for i in projects %}
  {% assign description-fr = i | append: "-desc-fr.md" %}
  {% if i == "11" %}
    {% assign image = i | append: "-teaser.gif" %}
  {% else %}
    {% assign image = i | append: "-teaser.png" %}
  {% endif %}
  {% include_relative {{description-fr}} %}
  ![]({{image}})
{% endfor %}
