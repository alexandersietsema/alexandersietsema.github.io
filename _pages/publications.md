---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<i>Last updated: Winter 2026. * indicates equal contribution.</i>
<br>
You can also find my articles on <u><a href="https://scholar.google.com/citations?hl=en&user=gi95kNwAAAAJ">my Google Scholar profile</a>.
<br>
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
