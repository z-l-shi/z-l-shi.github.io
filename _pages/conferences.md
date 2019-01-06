---
layout: archive
title: "Conferences"
permalink: /conferences/
author_profile: true
---

<!-- {% if site.author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %} -->

{% include base_path %}


{% for i in (2015..2020) %}
{{i}}
<table>
{% for post in site.conferences reversed %}
  {% assign datelist = post.date | Split: '-' %}
  {{datelist}}
  {{datelist[0]}}
  {{datelist[1]}}
  {% if post.date contains '2018' %}
      <tr>{% include publication.html %}</tr>
  {% endif %}
{% endfor %}
</table>

<!-- <table>
{% for post in site.conferences reversed %}
  <tr>{% include publication.html %}</tr>
{% endfor %}
</table> -->

{% endfor %}

