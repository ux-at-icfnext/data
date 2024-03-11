---
layout: layouts/collections
title: Drug Abuse Warning Network (DAWN)
subtitle: Title to introduce the page
short:  |
  The Drug Abuse Warning Network (DAWN) is a nationwide public health surveillance system that captures data on emergency department visits related to recent substance use and misuse directly from the electronic health records of participating hospitals. 
cycle: Annually
update: October 3, 2022
last: 2022
nav: dawn
---

<style>
a.hide-link {
  text-decoration: none;
  color: #1b1b1b;
}
img {
    max-width: 100%;
    max-height: 100%;
}
.button-list{
  display: flex;
  margin: 15px;
}

.box1 { grid-area: box1; }
.box2 { grid-area: box2; }
.box3 { grid-area: box3; }
.box4 { grid-area: box4; }
.box5 { grid-area: box5; }
.box6 { grid-area: box6; }
.box7 { grid-area: box7; }

@media screen and (max-width: 799px){
  .bento > div {
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
      "box5 box5 box5 box5"
      "box6 box6 box6 box6"
  }
  .bento2 {
    display: grid;
    grid-template-columns: auto;
    grid-template-rows: auto;
    column-gap: 10px;
    row-gap: 15px;
    grid-template-areas:
      "box1 box2 box2"
      "box1 box3 box3"
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
      "box3 box1 box1 box1 box4"
      "box5 box5 box5 box5 box5"
      "box2 box6 box6 box6 box6"
  }
  .bento2 {
    display: grid;
    grid-template-columns: auto;
    grid-template-rows: auto;
    column-gap: 10px;
    row-gap: 15px;
    grid-template-areas:
      "box1 box1 box2 box3"
  }
}
</style>

<div class="bento bento1">
  <div class="box1 usa-card__container"> 
  <a class="hide-link" href="/data-we-collect/dawn/annual/">
  <div class="usa-card__header"><h2 class="usa-card__heading">Annual Report</h2></div>
    <div class="usa-card__body">
      <p>
        250 characters -- that should includes mention of detail tables. -- Smiley was monstrous proud of his frog, and well he might.
      </p>
      <form class="usa-form data-drop">
        <label class="usa-label" for="options">Choose Year:</label>
        <select class="usa-select" name="options" id="options" onchange="window.open(this.value,'_self');">
          <option value>- Select Year -</option>
          <option value="/data-we-collect/dawn/release">2021</option>
          <option value="#">Option B</option>
          <option value="#">Option C</option>
        </select>
      </form>
    </div>
  </a>
  </div>
  <div class="box2 usa-card__container"> 
  <a class="hide-link" href="/data-we-collect/dawn/legacy/">
  <div class="usa-card__header"><h2 class="usa-card__heading">Legacy Dawn</h2></div>
    <div class="usa-card__body">
      <p>
        Smiley was monstrous proud of his frog, and well he might be, for fellers that had traveled and been everywheres, all said he laid over any frog that ever they see.
      </p>
    </div>
    </a>
  </div>
  <div class="box3 usa-card__container"> 
    <div class="usa-card__header"><h2 class="usa-card__heading">Title to a report - maximum length 140 characters before elipsis</h2></div>
    <div class="usa-card__body">
    <span class="usa-tag">Short Report</span>
      <p>
        Smiley was monstrous proud of his frog, and well he might be, for fellers that had traveled and been everywheres, all said he laid over any frog that ever they see.
      </p>
    </div>
  </div>
  <div class="box4 usa-card__container"> 
    <div class="usa-card__header"><h2 class="usa-card__heading">Title to a report - maximum length 140 characters before elipsis</h2></div>
    <div class="usa-card__body">
    <span class="usa-tag">Short Report</span>
      <p>
        Smiley was monstrous proud of his frog, and well he might be, for fellers that had traveled and been everywheres, all said he laid over any frog that ever they see.
      </p>
    </div>
  </div>
  <div class="box5 usa-card__container">
    <img src="/assets/siteimg/dawngraph.png"/>
  </div>
  <div class="box6 usa-card__container">
    <a class="hide-link" href="/data-we-collect/nsduh/about/">
    <div class="usa-card__header"><h2 class="usa-card__heading">Learn more about the DAWN Collection</h2></div>
    <div class="usa-card__body">
      <p>
        Smiley was monstrous proud of his frog, and well he might be, for fellers that had traveled and been everywheres, all said he laid over any frog that ever they see.
      </p>
    </div>
    </a>
  </div>
</div> <!-- close bento 1 -->

<h2>{title needed} Presentations, conference etc... </h2>
<div class="bento bento2">

<div class="box1 usa-card__container">
    <a class="hide-link" href="/data-we-collect/nsduh/about/">
    <div class="usa-card__header"><h2 class="usa-card__heading">Come see us a ### Con!</h2></div>
    <div class="usa-card__media">
        <div class="usa-card__img">
          <img
            src="https://designsystem.digital.gov/img/introducing-uswds-2-0/built-to-grow--alt.jpg"
            alt="A placeholder image"
          />
        </div>
    </div>
    <div class="usa-card__body">
      <span class="usa-tag">June 15th, 2024 | Washington DC</span>
      <p>
        Smiley was monstrous proud of his frog, and well he might be, for fellers that had traveled and been everywheres, all said he laid over any frog that ever they see.
      </p>
    </div>
    </a>
  </div>
  <div class="box2 usa-card__container"> 
    <div class="usa-card__header"><h2 class="usa-card__heading">Title to a report - maximum length 140 characters before elipsis</h2></div>
    <div class="usa-card__body">
    <span class="usa-tag">Tag Report</span>
      <p>
        Smiley was monstrous proud of his frog, and well he might be, for fellers that had traveled and been everywheres, all said he laid over any frog that ever they see.
      </p>
    </div>
  </div>
  <div class="box3 usa-card__container"> 
    <div class="usa-card__header"><h2 class="usa-card__heading">Title to a report - maximum length 140 characters before elipsis</h2></div>
    <div class="usa-card__body">
    <span class="usa-tag">Tag Report</span>
      <p>
        Smiley was monstrous proud of his frog, and well he might be, for fellers that had traveled and been everywheres, all said he laid over any frog that ever they see.
      </p>
    </div>
  </div>

</div> <!-- close bento 2 -->