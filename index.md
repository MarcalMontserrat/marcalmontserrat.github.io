---
layout: default
title: Home
---

{% include navigation.html %}

## Welcome to Marmonca's blog

This is my personal blog and i will talk about .Net topics.

{% for category in site.categories %}
  <h3>{{ category[0] }}</h3>
  <ul>
    {% for post in category[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}
