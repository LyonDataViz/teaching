---
layout: default
---

## Gallerie des projets

[In english](./index.html)

{% assign projects = "12,11,15,9,19,6,20,18,10,4,5,2,8,7,1," | split: "," %}

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
