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
　　I am currently a professor of [South China University of Technology](https://www.scut.edu.cn/new/), received a _PhD_ in Computer Science from [Nanyang Technological University](https://www.ntu.edu.sg/Pages/home.aspx) in Singapore in 2014 and complete post-doctoral research in computer vision in [The University of Adelaide](https://www.adelaide.edu.au/) in Australia in 2016. My research interest focuses on machine learning algorithms and theories, computer vision. Up to now, I have published nearly 50 high-level academic papers in relevant directions.

Publications
----------
*******
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
