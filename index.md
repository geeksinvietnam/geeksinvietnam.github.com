---
layout: page
title: Hello World!
tagline: self.__init__()
---
{% include JB/setup %}

## Un voyage au Vietnam

Suivez nos aventures au Vietnam sur [Github](http://geeksinvietnam.github.io) et [Twitter](http://twitter.com/geeksinvietnam)… comme ça vous saurez si ça compile.

Aujourd'hui : J0x2, Hồ Chí Minh Ville (Saïgon).

<section class="content">
  <ul class="listing">
    {% for post in site.posts %}
    <li>
      <span>{{ post.date | date: "%B %e, %Y" }}</span> <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
    {% endfor %}
  </ul>
</section>
