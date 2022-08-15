## Welcome to Funky Bookends Bliki

This is a place for me to track the interesting software engieering videos and posts that I have come across.

# Posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
