---
layout: default
---

## Project Gallery

[En français](./index-fr.html)

{% assign projects = "4,3,12,2,5,33,11,10,1,100,0,9,7,8,47,69,42,72,6" | split: "," %}

{% for i in projects %}
  {% assign description-en = i | append: "-desc-en.md" %}
  {% assign image = i | append: "-teaser.png" %}
  {% include_relative {{description-en}} %}
  ![]({{image}})
{% endfor %} 


<!-- {% include_relative 0-desc-fr.md %} -->