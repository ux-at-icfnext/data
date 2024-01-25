<div>

### What's in the section

<ul class="usa-sidenav">
  {% for item in collection.nav %}
    <li class="usa-sidenav__item"><a href="{{ item.href}}"{% if page.url == item.href %} class="usa-current" {% endif %} > {{ item.title }}</a></li>
    {% endfor %}
</ul>
</div>