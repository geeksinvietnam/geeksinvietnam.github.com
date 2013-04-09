---
layout: page
---
{% include JB/setup %}

## Un voyage au Vietnam

Suivez nos aventures au Vietnam sur [Github](http://geeksinvietnam.github.io) et [Twitter](http://twitter.com/geeksinvietnam)… comme ça vous saurez si ça compile.

Aujourd'hui : J0x2, Hồ Chí Minh Ville (Saïgon).

{% for post in site.posts limit: 5 %}
<div class="page-header">
  <h1>
    <a href="{{ post.url }}">{{ post.title }}</a> ({{ post.date | date:"%Y-%m-%d" }})
    {% if post.tagline %}
      <small>{{ post.tagline }}</small>
    {% endif %}
  </h1>
</div>
<div class="row">
 <div class="span8">
  {{ post.content }}
 </div>
</div>
{% endfor %}
