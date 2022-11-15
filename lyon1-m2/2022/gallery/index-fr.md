---
layout: default
---

## Gallerie des projets

[In english](./index.html)

{% assign projects = "2,3,4,13,6,9,10,11,12,13,14,1,15" | split: "," %}

{% for i in projects %}
  {% assign description-fr = i | append: "-desc-fr.md" %}
  {% if i == "10" %}
    {% assign image = i | append: "-thumbnail.gif" %}
  {% else %}
    {% if i == "9" %}
      {% assign image = "" %}
    {% else %}
      {% assign image = i | append: "-thumbnail.png" %}
    {% endif %}
  {% endif %}
  {% include_relative {{description-fr}} %}
  ![]({{image}})
{% endfor %}
