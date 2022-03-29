---
layout: home
profile_picture:
  src: /assets/img/profile-pic.jpg
  alt: website picture
---

<h3>{{site.data.home.hello.title}}</h3>
<p>{{site.data.home.hello.subtitle}}</p>
<h3>{{site.data.home.about.title}}</h3>

  {% for bullet in site.data.home.about.bullets %}
  <p>{{bullet}}</p>
  {% endfor %}
