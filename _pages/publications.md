---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

{% for post in site.publications reversed %}
  {% if post.collection == 'publications' %}
    {% include archive-single.html %}
    {% endif %}
{% endfor %}

**Under Review**

{% for post in site.publications reversed %}
  {% if post.collection == 'underreview' %}
    {% include archive-single.html %}
    {% endif %}
{% endfor %}
