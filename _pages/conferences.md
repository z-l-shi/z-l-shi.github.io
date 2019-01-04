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

{% assign year = 2018 %}
{% for post in site.conferences reversed %}
{% if post.date %}
  {% if year != post.date | default: "1900-01-01" | date: "%Y"%}
    {% assign year = post.date | default: "1900-01-01" | date: "%Y" %}
    {if}
    {{ post.date | default: "1900-01-01" | date: "%Y" }}
    {{year}}
  {% else %}
    {else}
    {{ post.date | default: "1900-01-01" | date: "%Y" }}
    {{year}}
  {% endif %}
{% endif %}
{% endfor %}
