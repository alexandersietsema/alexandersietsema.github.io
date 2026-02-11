---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<i>Last updated: Winter 2026. * indicates equal contribution.</i>
<br>
<br>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
