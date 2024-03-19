---
layout: base.html
title: home

list:
  - title: Survey Collection Pages (NSDUH)
    link: /data-we-collect/nsduh/
  - title: Survey Collection Pages (MH-CLD)
    link: /data-we-collect/mhcld/
  - title: Survey Collection Pages (DAWN)
    link: /data-we-collect/dawn/
  - title: Survey Collection Pages (N-SUMHSS)
    link: /data-we-collect/numhss/
  - title: Analyze Data (TEDS) - To show example of Quick Stats
    link: /data-we-collect/teds/analyze/
---
<div class="grid-container usa-prose" style="margin-top: 50px;">

# Prototypes for CHSBQ

<ul>
{% for l in list %}
<li><a href="{{ l.link }}">{{ l.title }}</a></li>
{% endfor %}
</ul>

</div>