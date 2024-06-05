---
layout: layouts/collections
title: Treatment Episode Data Set (TEDS)
subtitle: Analysis Tools
short:  |
  When undergoing substance abuse treatment, individual people can be admitted and discharged from treatment multiple times. The Treatment Episode Data Set (TEDS) system comprises demographic and drug history information about these individuals.
cycle: Annually
update: October 3, 2022
last: 2021
nav: teds
---
<style>
.data-download {
    background-color: #cccccc;
    padding: 15px;
}
.data-drop {
  display: flex;
  margin-bottom: 5px;
  width: 100%;
}
.usa-label {
  font-weight: 700;
  padding-right: 5px;
  width: 70px;
}

.usa-select{
  width: 155px;
  margin-right: 30px;
}
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
<a href="#" class="usa-button">Go to DAS</a>
</div>
<div class="box3">
  <img src="https://place-hold.it/500x300" />
</div>
<div class="box4">
<h3>Quick Statistics</h3>
<p>TEDS Quick Statistics include quarterly updated admission and discharge data on clients aged 12 years and older by primary substance use, gender, age, race, and ethnicity.</p>
<p><a href="#" class="usa-button">Get Stats</a></p>
</div>
<div class="box5">
<h4>Learn more about analyzing data online with the <a href="#">Data Tools</a> site</h4>
</div>
</div>