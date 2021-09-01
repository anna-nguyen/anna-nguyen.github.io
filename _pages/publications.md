---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

{% for post in site.publications reversed %}
  {% if post.venue != 'Under Review' %}
    {% include archive-single.html %}
    {% endif %}
{% endfor %}

**Under Review**

{% for post in site.publications reversed %}
  {% if post.venue == 'Under Review' %}
    {% include archive-single.html %}
    {% endif %}
{% endfor %}
