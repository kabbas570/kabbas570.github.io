---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-thumbnail.html %}
{% endfor %}

{% assign sorted_publications = site.publications | sort: "weight" %}
{% for publication in sorted_publications %}
  <h2>{{ publication.title }}</h2>
  {{ publication.content }}
{% endfor %}

