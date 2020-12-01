---
layout: default
---

## Project Gallery

[En français](./index-fr.html)

{% assign projects = "12,11,15,9,19,6,20,18,10,4,5,2,8,7,1" | split: "," %}

{% for i in projects %}
  {% assign description-en = i | append: "-desc-en.md" %}
  {% if i == "11" %}
    {% assign image = i | append: "-teaser.gif" %}
  {% else %}
    {% assign image = i | append: "-teaser.png" %}
  {% endif %}
  {% include_relative {{description-en}} %}
  ![]({{image}})
{% endfor %}
