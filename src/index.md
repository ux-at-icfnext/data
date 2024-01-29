---
layout: base.html
title: home

list:
  - title: Survey Collection Pages (NSDUH)
    link: /data-we-collect/nsduh/
---
<div class="grid-container usa-prose" style="margin-top: 50px;">

# Prototypes for CHSBQ

<ul>
{% for l in list %}
<li><a href="{{ l.link }}">{{ l.title }}</a></li>
{% endfor %}
</ul>

</div>