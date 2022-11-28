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
　　I am currently a Professor with the School of Future Technology at South China University of Technology. I received my Bachelor and Master degrees from Harbin Engineering University, Harbin, China, in 2013 and 2016, respectively, and the Ph.D degree in Electrical Engineering from City University of Hong Kong, Hong Kong, China, in 2019. During 2018 - 2019, I was a Visiting Scholar at University of California Davis, CA, USA. From 2019 to 2022, I worked as a Research Fellow in the Department of Electrical and Computer Engineering, National University of Singapore, Singapore. My research interests include machine learning, optimization methods, and neuromorphic computing with applications to image/video/speech/radar signal processing. 

Journals
----------
<div>
  <table>
  {% for post in site.journals_main reversed %}
    <tr>{% include publication.html %}</tr>
  {% endfor %}
  </table>
   <a href="/journals/">
    <button class="btn btn--readmore">Read more <font size="1">>></font></button>
  </a>
</div>

<!-- <div margin-bottom:100px>
  <a href="/journals/">
    <button class="btn btn--readmore">Read more <font size="1">>></font></button>
  </a>
</div>  -->




