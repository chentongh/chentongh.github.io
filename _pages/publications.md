---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">My publication can be found on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

<!-- {% include base_path %} -->

<!-- New style rendering if publication categories are defined -->
<!--
{% if site.publication_category %}
  {% for category in site.publication_category  %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        <h2>{{ category[1].title }}</h2><hr />
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %}
-->


## Conference Papers
---
\* represents equal contribution


## Journal Papers
---
\* represents equal contribution

- **Chentong Huang**, Junming Hou, Chenxu Wu, Xiaofeng Cong, Man Zhou, Junling Li, Danfeng Hong, [A General Cooperative Optimization Driven High-Frequency Enhancement Framework for Multi-Spectral Image Fusion](https://ieeexplore.ieee.org/abstract/document/10897307). IEEE Transactions on Geoscience and Remote Sensing (TGRS), 2025


