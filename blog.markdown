Blog
----

Welcome to my blog.  Here are the posts I've made:

<ul>
  {% for post in site.posts %}
  <li>
    <a href="{{ post.url }}" title="{{ post.title }}">{{post.title}}</a>
  </li>
  {% endfor %}
</ul>
