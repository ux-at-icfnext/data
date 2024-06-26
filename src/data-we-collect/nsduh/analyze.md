---
layout: layouts/collections
title: National Survey on Drug Use and Health (NSDUH)
subtitle: Analyze Data Online
short:  |
  The data provide estimates of substance use and mental illness at the national, state, and substate levels. NSDUH data also help to identify the extent of substance use and mental illness among different subgroups, estimate trends over time, and determine the need for treatment services.
cycle: Annually
update: October 3, 2022
last: 2021
nav: nsduh
---
<style>
img {
    max-width: 100%;
    max-height: 100%;
}
.box1 { grid-area: box1; }
.box2 { grid-area: box2; }
.box3 { grid-area: box3; }
.box4 { grid-area: box4; }
.box5 { 
  grid-area: box5; 
  border: 1px solid #000;
  text-align: center;
  background-color: #eee;
}
.box6 { grid-area: box6; }
.box7 { grid-area: box7; }

@media screen and (max-width: 799px){
  .bento > div {
    margin-bottom: 15px;
  }
}

@media screen and (min-width: 800px){
  .bento {
    display: grid;
    grid-template-columns: auto;
    grid-template-rows: auto;
    column-gap: 20px;
    row-gap: 25px;
    grid-template-areas:
      "box2 box1 box1"
      "box3 box3 box4"
      "box5 box5 box5"
  }
</style>

Lorem ipsum dolor sit amet consectetur. Vestibulum urna sit eu lacinia. Est sed praesent odio nec risus. Felis aliquet dui dolor nibh. Ut eros vulputate a arcu sit pulvinar etiam semper nibh tincidunt. {: .usa-intro }

<div class="bento">
<div class="box1">
  <img src="https://place-hold.it/500x300" />
</div>
<div class="box2">
<h3>Data Analysis System</h3>
<p>Lorem ipsum dolor sit amet consectetur. Vestibulum urna sit eu lacinia. Est sed praesent odio nec risus. Felis aliquet dui dolor nibh. Ut eros vulputate a arcu sit pulvinar etiam semper nibh tincidunt.</p>
<p class="das-link" style="display: flex; gap: 10px; align-items: baseline;">
  <select class="usa-select" style="max-width: 100px;" name="options" id="options">
    <option value>2019</option>
    <option value="value1">2021</option>
    <option value="value2">2019</option>
    <option value="value3">2018</option>
  </select>
  <select class="usa-select" style="max-width: 160px;" name="options" id="options">
    <option value>Choose Data Set</option>
    <option value="value1">NSDUH: Public-use Data (2019)</option>
    <option value="value2">NSDUH: Combined Public-use File (2002-2019)</option>
    <option value="value3">NSDUH: 2-Year Restricted-use Data (2018-2019)</option>
    <option value="value3">NSDUH: 10-Year Substate Restricted-use Data (2010-2019)</option>
  </select>
  <a href="#" class="usa-button">Go to DAS</a>
</p>
</div>
<div class="box3">
  <img src="https://place-hold.it/500x300" />
</div>
<div class="box4">
<h3>State Estimates</h3>
<p>Lorem ipsum dolor sit amet consectetur. Vestibulum urna sit eu lacinia. Est sed praesent odio nec risus. Felis aliquet dui dolor nibh. Ut eros vulputate a arcu sit pulvinar etiam semper nibh tincidunt.</p>
<p><a href="#" class="usa-button">Visualize State Data</a></p>
<p>
  <a href="#" class="usa-button">Visualize Substate Regional Data</a>
</p>
</div>
<div class="box5">
<h4>Learn more about analyzing data online with the <a href="#">Data Tools</a> site</h4>
</div>
</div>