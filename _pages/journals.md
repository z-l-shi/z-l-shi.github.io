---
layout: archive
title: "Journals"
permalink: /journals/
author_profile: true
---

{% if site.author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<table>
{% for post in site.journals reversed %}
  <tr>{% include publication.html %}</tr>
{% endfor %}
</table>
