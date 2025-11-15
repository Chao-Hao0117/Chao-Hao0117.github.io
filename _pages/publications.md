---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

## Master Thesis

{% for post in site.publications reversed %}
  {% if post.type == 'Thesis' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

---

## Journal Papers

{% for post in site.publications reversed %}
  {% if post.type == 'Paper' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
