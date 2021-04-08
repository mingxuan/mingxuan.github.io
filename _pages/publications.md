---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


{% include base_path %}

## Conference Papers
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Pre-prints (In progress)
{% for post in site.arxiv reversed %}
  {% include archive-single.html %}
{% endfor %}


