<div class="usa-accordion">
{% for item in items %}
  <span class="usa-accordion__heading">
      <button
      class="usa-accordion__button"
      aria-expanded="false"
      aria-controls="{{ set.ref | default: 'a' }}{{forloop.index}}"
      >
          {{ item.title }}
      </button>
  </span>
  <div id="{{ set.ref | default: 'a' }}{{forloop.index}}" class="usa-accordion__content usa-prose">
{% if item.header %} 
    <h2> {{ item.header }}</h2>
{% endif %}
    {{ item.content | markdownify }}
  </div>
{% endfor %}
</div>