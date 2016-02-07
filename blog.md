---
layout: page
title: Blog
permalink: /blog/
---

Useful blogs convey opinions on important issues. Artistic blogs have photographs, paintings,
poetry or literature. Informative blogs contain tutorials on cooking, coding, making etc.
This blog is none of these -- it is a collection of rants and existential crises from my
post PhD life. I am led to believe that you can follow this sporadically updated
blog using this [RSS feed](/atom.xml), assuming that you like feeds.

<ul class="listing">
{% for post in site.posts %}
  {% capture y %}{{post.date | date:"%Y"}}{% endcapture %}
  {% if year != y %}
    {% assign year = y %}
    <li class="listing-seperator">{{ y }}</li>
  {% endif %}
  <li class="listing-item">
    <time datetime="{{ post.date | date:"%Y-%m-%d" }}">{{ post.date | date:"%Y-%m-%d" }}</time>
    <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>
