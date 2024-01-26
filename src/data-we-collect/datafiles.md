---
layout: layouts/collections
title: National Survey on Drug Use and Health (NSDUH)
subtitle: Download Data Files
short:  |
  The data provide estimates of substance use and mental illness at the national, state, and substate levels. NSDUH data also help to identify the extent of substance use and mental illness among different subgroups, estimate trends over time, and determine the need for treatment services.
cycle: Annually
update: October 3, 2022
last: 2021
---
<style>
  .data-download {
    background-color: #cccccc;
    padding: 15px;
  }
  .data-drop {
    margin-bottom: 5px;
    width: 100%;
  }
  .usa-label {
    font-weight: 700;
  }

  @media screen and (min-width: 800px){
    .usa-label {
      width: 20%;
    }
    .data-drop {
      display: flex;
    }
     .datasets {
      display: flex;
      width: 100%;
      justify-content: space-between;
    }
  }
  .datasets {
    margin-top: 20px;
    width: 100%;
  }
  
</style>

## {{ subtitle }}

Lorem ipsum dolor sit amet consectetur. Habitasse leo odio sem enim placerat pellentesque auctor magna. Sit arcu in sit suspendisse etiam faucibus tortor. Pulvinar vitae orci quisque vel convallis non. {: .usa-intro }

**Geographic Coverage:** United States
**Unit of Observation:** Individual
**Data Types:** Survey Data
**Universe:** Civilian, noninstitutionalized population of the United States aged 12 and older, including residents of noninstitutional group quarters such as college dormitories, group homes, shelters, rooming houses, and civilians living on military installations.

<div class="data-download">
    <div class="data-drop">
      <label class="usa-label" for="year">Choose Year</label>
        <div class="usa-combo-box">
          <select class="usa-select" name="year" id="year">
            <option value>2021</option>
          </select>
        </div>
    </div>
    <div class="data-drop">
      <label class="usa-label" for="year">Choose Collection</label>
        <div class="usa-combo-box">
          <select class="usa-select" name="year" id="year">
            <option value>Public-use Data 2021</option>
          </select>
        </div>
    </div>
  
  <div class="datasets">
    <div> 
      Dataset Documentation <br/>
      <a href="#">Cookbook.pdf</a><br/>
      <a href="#">Questionnaire-Specs.pdf</a><br/>
      <a href="#">Questionnaire-Showcards.pdf</a><br/>
    </div>
    <div>
      Dataset Downloads<br/>
      <a href="#">SAS</a>
      <a href="#">SPSS</a>
      <a href="#">Stata</a>
      <a href="#">ASCII</a>
      <a href="#">Delimited</a>
      <a href="#">R</a><br/>
      <a href="#">SAS Setup</a>
      <a href="#">SPSS Setup</a>
      <a href="#">Stata Setup</a>
    </div>
  </div>
  <h4 class="usa-accordion__heading">
    <button
      type="button"
      class="usa-accordion__button"
      aria-expanded="false"
      aria-controls="a1"
    >
      Related Files
    </button>
  </h4>
</div> <!-- close download -->

### Variable Crosswalk Charts
There have been changes to the questionnaire and variable definitions over the years. For those who want to make trends or pool data, it is important that the variable be comparable over the period of interest. These charts list all available variables for each dataset and for each one lists 1) whether it was available in the given year and 2) whether it was comparable to the previous year(s). Crosswalks go back to 2002.

In 2021, due to the addition of web interviewing, a new crosswalk chart was started. Data from 2021 and the years that follow cannot be compared or pooled with earlier years for any variable, so the crosswalk chart only includes data from 2021 and onward.

The following variable crosswalk charts are available for public use files and the Restricted Use data files (RUFs):

- [PUF Variable Crosswalk Chart: 2021 and 2022 (xlsx)](#)
- [PUF Variable Crosswalk Chart: 2019 and Prior (xlsx)](#)
- [RUFs Variable Crosswalk Chart: Multi-Year (xlsx)](#)
{: .usa-list}

<h4 class="usa-accordion__heading">
    <button
      type="button"
      class="usa-accordion__button"
      aria-expanded="false"
      aria-controls="a1"
    >
      {i} History of NSDUH
    </button>
  </h4>
  <h4 class="usa-accordion__heading">
    <button
      type="button"
      class="usa-accordion__button"
      aria-expanded="false"
      aria-controls="a1"
    >
      {i} Study Notes
    </button>
  </h4>
  <h4 class="usa-accordion__heading">
    <button
      type="button"
      class="usa-accordion__button"
      aria-expanded="false"
      aria-controls="a1"
    >
      {i} Methodology
    </button>
  </h4>