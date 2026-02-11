---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<i>Last updated: Winter 2026. ∗ indicates equal contribution.</i>

You can also find my articles on <u><a href="https://scholar.google.com/citations?hl=en&user=gi95kNwAAAAJ">my Google Scholar profile</a>.
<br>
{% include base_path %}

<h2>Journal Publications</h2>
{% for post in site.publications reversed %}
  {% if post.type == "jpublications" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<h2>Conference Publications</h2>
{% for post in site.publications reversed %}
  {% if post.type == "cpublications" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
