<div>

### What's in this section

<ul class="usa-sidenav side-nav">
{% for item in collection[nav] %}
  <li class="usa-sidenav__item"><a href="{{ item.href}}"{% if page.url == item.href %} class="usa-current" {% endif %} > {{ item.title }}</a></li>
{% endfor %}
</ul>
</div>
<div class="side-nav-sm">
<h4 class="usa-accordion__heading">
    <button
      type="button"
      class="usa-accordion__button"
      aria-expanded="false"
    >
      What's in this section
    </button>
  </h4>
</div>