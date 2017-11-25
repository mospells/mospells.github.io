---
layout: home
excerpt:
header:
  overlay_image: https://3.bp.blogspot.com/-fq-pJIzpXB8/WJuok4P3jeI/AAAAAAAAAbk/nkIURb2-zSglA6Vvh-g-H_u1B9MS_Qg5QCLcB/s1600/IMG_1170.JPG
  caption: "Photo credit: **University of Baltimore Special Collections**"
classes:
  - landing
  - dark-theme
---
# Blog

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
