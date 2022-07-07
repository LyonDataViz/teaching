---
layout: default
---

## Project Gallery

[En français](./index-fr.html)

{% assign projects = "1,2,3,4,6,9,10,11,12,13,14,15" | split: "," %}

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
