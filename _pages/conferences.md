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
  {% if post.date contains '2018' %}
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

#### 2016
#### 2015
#### 2014