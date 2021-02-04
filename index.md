<nav>
  <ul>
   {% for item in site.data.main %}
      <li><a href="{{ item.url }}">{{ item.title }}</a></li>
   {% endfor %}
</ul>
</nav>
