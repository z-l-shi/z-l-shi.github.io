---
layout: archive
title: "Conferences"
permalink: /conferences/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<table>
{% for post in site.conferences reversed %}
  <tr>{% include publication.html %}</tr>
{% endfor %}
</table>


{% for post in site.conferences reversed %}
{% if post.date %}
  {% assign year = post.date %}
  {{ post.date | default: "1900-01-01" | date: "%Y" }}
  {{year}}
{% endif %}
{% endfor %}
