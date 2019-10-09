---
layout: single
title: ""
excerpt: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

# Journal articles

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

# Working papers

{% for post in site.wp reversed %}
  {% include archive-single.html %}
{% endfor %}
