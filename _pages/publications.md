---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

#{% if author.googlescholar %}
You can find my complete list of scientific work on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
#{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
