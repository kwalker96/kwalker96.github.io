---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
You can find all my articles on my [Google Scholar profile](https://scholar.google.co.uk/citations?user=cZDL820AAAAJ&hl=en), with a subset linked below:

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
