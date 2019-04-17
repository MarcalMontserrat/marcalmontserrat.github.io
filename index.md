## Welcome to Marmonca's blog

This is my personal blog and i will talk about .Net topics.


<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
