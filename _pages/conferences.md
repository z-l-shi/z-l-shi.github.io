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

## 2018

<table>
{% for post in site.conferences reversed %}
  {% if "2018-07-01" == post.date | default: "1900-01-01" | date: "%Y" %}
    <tr>{% include publication.html %}</tr>
  {% endif %}
{% endfor %}
</table>

## 2017

<table>
{% for post in site.conferences reversed %}
  <tr>{% include publication.html %}</tr>
{% endfor %}
</table>

# 2016
## 2015