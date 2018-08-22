
## Welcome to Credco Internal Site

Hello World!

### Recent posts

<ul>
{% for item in site.posts %}
  <li><a href="{{ item.url }}">{{ item.title }}</a></li>
{% endfor %}
</ul>

### Support or Contact

[{{ site.email }}](mailto:{{ site.email }})

[@credcoalition](https://twitter.com/credcoalition)
