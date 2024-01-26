---
layout: base
---
<style>
  @media screen and (max-width: 799px){
    .side-nav {
      display: none;
    }
  }
  @media screen and (min-width: 800px){
    .side-nav {
      display: block;
    }
    .side-nav-sm {
      display: none;
    }
  }
</style>
{% include "patterns/hero/collection-hero.md" %}
<div class="grid-container grid-row grid-gap">
<div class="section-nav tablet:grid-col-3">{% include "patterns/sidenav/collection-nav.md" %}</div>

<div class="section-nav tablet:grid-col-9">

{{ content }}

</div> <!-- close body -->
</div><!-- close grid --> 
<p> footer here </p>