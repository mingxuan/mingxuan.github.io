---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on my [Google Scholar Profile](https://scholar.google.com/citations?user=cB1mFBsAAAAJ)<br>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

