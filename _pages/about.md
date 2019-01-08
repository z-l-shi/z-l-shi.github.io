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
　　Received my Bachelor Degree in Environmental Science and Engineering in 2006 and Master degree in Control Science and Engineering in 2009, both from Hunan University in Changsha, China. I received the PhD degree in Computer Science from Nanyang Technological University, Singapore, in 2014. From 2014-2016, I worked as a Senior Research Associate on computer vision in the School of Computer Science, University of Adelaide, Australia. Since 2016, I have been with the School of Software Engineering, South China University of Technology, China, where I am currently a Professor. My research interests include machine learning, sparse analysis, deep learning and large-scale optimization.

Conferences
----------
<div>
  <table>
  {% for post in site.conferences_main reversed %}
    <tr>{% include publication.html %}</tr>
  {% endfor %}
  </table>
</div>

<div margin-bottom:100px>
  <a href="/conferences/">
    <button class="btn btn--readmore">Read more <font size="1">>></font></button>
  </a>
</div> 


Journals
----------
<div>
  <table>
  {% for post in site.journals_main reversed %}
    <tr>{% include publication.html %}</tr>
  {% endfor %}
  </table>
</div>

<div margin-bottom:100px>
  <a href="/journals/">
    <button class="btn btn--readmore">Read more <font size="1">>></font></button>
  </a>
</div> 


Preprint Paper
----------
<div>
  <table>
  {% for post in site.preprints reversed %}
    <tr>{% include publication.html %}</tr>
  {% endfor %}
  </table>
</div>

