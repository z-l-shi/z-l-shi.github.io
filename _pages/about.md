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
　　Mingkui Tan is currently a professor of [South China University of Technology](https://www.scut.edu.cn/new/), and is a member of the _National Central Group Youth 1000 Program_, a core member of the _“Pearl River Talent Team”_ in Guangdong Province. Professor Mingkui Tan received a _PhD_ in Computer Science from [Nanyang Technological University](https://www.ntu.edu.sg/Pages/home.aspx) in Singapore in 2014 and complete post-doctoral research in computer vision in [The University of Adelaide](https://www.adelaide.edu.au/) in Australia in 2016. At present, the main research interests are machine learning algorithms and theories, computer vision, and He has published nearly 50 high-level academic papers in relevant directions.

Publications
----------
*******
<table>
{% for post in site.aboutme reversed %}
  <tr>{% include publication.html %}</tr>
{% endfor %}
</table>

<div margin-bottom:100px>
  <a href="/publications/">
    <button class="btn btn--readmore">Read more <font size=5>>></font></button>
  </a>
</div> 
