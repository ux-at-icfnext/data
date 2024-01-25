---
layout: base
title: National Survey on Drug Use and Health (NSDUH)
subtitle: Latest Release
short:  |
  The data provide estimates of substance use and mental illness at the national, state, and substate levels. NSDUH data also help to identify the extent of substance use and mental illness among different subgroups, estimate trends over time, and determine the need for treatment services.
cycle: Annually
update: October 3, 2022
last: 2021
---
<style>
a.hide-link {
  text-decoration: none;
  color: #1b1b1b;
}
img.bento {
    max-width: 100%;
    max-height: auto;
}
.box1 { grid-area: box1; }
.box2 { grid-area: box2; }
.box3 { grid-area: box3; }
.box4 { grid-area: box4; }
.box5 { grid-area: box5; }
.box6 { grid-area: box6; }
.box7 { grid-area: box7; }

@media screen and (max-width: 799px){
  .bento1 > div {
    margin-bottom: 15px;
  }
}
@media screen and (min-width: 800px){
  .bento1 {
    display: grid;
    grid-template-columns: auto;
    grid-template-rows: auto;
    column-gap: 10px;
    row-gap: 15px;
    grid-template-areas:
      "box1 box1 box1 box2"
      "box3 box3 box4 box4"
      "box5 box5 box6 box6"
      "box7 box7 box7 box7"
  }
}

@media screen and (min-width: 1200px){
  .bento1 {
    display: grid;
    grid-template-columns: auto;
    grid-template-rows: auto;
    column-gap: 10px;
    row-gap: 15px;
    grid-template-areas:
      "box1 box1 box1 box2"
      "box3 box5 box5 box4"
      "box3 box6 box6 box4"
      "box7 box7 box7 box7"
  }
}
</style>
{% include "patterns/hero/collection-hero.md" %}
<div class="grid-container grid-row">
<div class="section-nav tablet:grid-col-3">in page nav here</div>

<div class="section-nav tablet:grid-col-9">

## Title to introduce the page

<div class="bento bento1">
  <div class="box1 usa-card__container">
    <a class="hide-link" href="/">
    <div class="usa-card__header"><h2 class="usa-card__heading">Annual Report Title</h2></div>
    <div class="usa-card__body">
      <p>
        Smiley was monstrous proud of his frog, and well he might be, for fellers that had traveled and been everywheres, all said he laid over any frog that ever they see.
      </p>
    </div>
    </a>
  </div>
  <div class="box2 usa-card__container">
    <div class="usa-card__body">
      <a href="/">View latest annual release </a></br>
      <label class="usa-label" for="year">View a previous year</label>
      <div class="usa-combo-box">
        <select class="usa-select" name="year" id="year">
          <option value>Select year</option>
        </select>
      </div>
    </div>
  </div>
  <div class="box3 usa-card__container">
    <a class="hide-link" href="/">
    <div class="usa-card__header"><h2 class="usa-card__heading">State Report</h2></div>
    <div class="usa-card__body">
      <p>
        Smiley was monstrous proud of his frog, and well he might be, for fellers that had traveled and been everywheres, all said he laid over any frog that ever they see.
      </p>
    </div>
    </a>
  </div>
  <div class="box4 usa-card__container">
    <a class="hide-link" href="/">
    <div class="usa-card__header"><h2 class="usa-card__heading">Substate Report</h2></div>
    <div class="usa-card__body">
      <p>
        Smiley was monstrous proud of his frog, and well he might be, for fellers that had traveled and been everywheres, all said he laid over any frog that ever they see.
      </p>
    </div>
    </a>
  </div>
  <div class="box5 usa-card__container">
    <a class="hide-link" href="/">
    <img
            src="https://designsystem.digital.gov/img/introducing-uswds-2-0/built-to-grow--alt.jpg"
            alt="A placeholder image"
          />
    </a>
  </div>
  <div class="box6 usa-card__container">
    <a class="hide-link" href="/">
    <div class="usa-card__header"><h2 class="usa-card__heading">Download Files</h2></div>
    <div class="usa-card__body">
      <p>
        Smiley was monstrous proud of his frog
      </p>
    </div>
    </a>
  </div>
  <div class="box7 usa-card__container">
    <a class="hide-link" href="/">
    <div class="usa-card__header"><h2 class="usa-card__heading">Learn more about the NSDUH Collection</h2></div>
    <div class="usa-card__body">
      <p>
        Smiley was monstrous proud of his frog, and well he might be, for fellers that had traveled and been everywheres, all said he laid over any frog that ever they see.
      </p>
    </div>
    </a>
  </div>
</div>
</div> <!-- close body -->
</div><!-- close grid --> 