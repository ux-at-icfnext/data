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
  .place-block {
    background-color: aliceblue;
    margin: 0;
    padding: 20px;
  }
  footer.place-block { margin-top: 20px;}
</style>
<header class="place-block">SAMHSA Header Here</header>

{% include "patterns/hero/collection-hero.md" %}
<div class="grid-container grid-row grid-gap">
<div class="section-nav tablet:grid-col-3">{% include "patterns/sidenav/collection-nav.md" %}</div>

<div class="section-nav tablet:grid-col-9">

## {{ subtitle }}
{{ content }}

</div>
</div>

<footer class="place-block">SAMHSA Footer Here</footer>