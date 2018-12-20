---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<br />
　　I am a professor of the South China University of Technology. In 2014,  I received a PhD in Computer Science from Nanyang Technological University in Singapore, and I complete post-doctoral research in computer vision at the University of Adelaide in Australia in 2016.My research interest focuses on machine learning algorithms and theories, computer vision. Up to now,  I have published nearly 50 high-level academic papers in relevant directions.

Publications
----------
<div>
  <table>
  {% for post in site.aboutme reversed %}
    <tr>{% include publication.html %}</tr>
  {% endfor %}
  </table>
</div>

<div margin-bottom:100px>
  <a href="/publications/">
    <button class="btn btn--readmore">Read more <font size="1">>></font></button>
  </a>
</div> 
