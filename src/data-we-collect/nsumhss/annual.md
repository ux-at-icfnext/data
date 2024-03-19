---
layout: layouts/collections
title: National Substance Use and Mental Health Services Survey (N-SUMHSS)
subtitle: Annual Report
short:  |
  The National Substance Use and Mental Health Services Survey (N-SUMHSS) is a survey of all substance use and mental health treatment facilities in the United States, its territories, and the District of Columbia, sponsored by the Substance Abuse and Mental Health Services Administration (SAMHSA).
cycle: Annually
update: October 3, 2022
last: 2021
nav: nsumhss
---


<style>
.reports {
  border-bottom: 1px solid #000;
  margin-bottom: 15px;
}
.reports > h3 {
  padding: 0;
  margin: 0;
  color: #005ea2;
}
.meta {
  font-size: 14px;
  padding: 0;
  margin: 0;
  margin-bottom: 5px;
}
.data-drop {
    margin-bottom: 20px;
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
}
</style>

Annual reports are produced every year, presenting information from a single data source. {: .usa-intro }

**Location:** National
**Format:** PDF or HTML

<div class="data-drop">
  <label class="usa-label" for="year">Choose Collection</label>
    <div class="usa-combo-box">
      <select class="usa-select" name="year" id="year">
        <option value>N-SUMHSS</option>
        <option value>N-MHSS</option>
        <option value>N-SSATS</option>
      </select>
    </div>
</div>

{% for i in (1..2) %}
<div class="reports">

### National Substance Use And Mental Health Services Survey (N-SUMHSS)
Published Date: November 4, 2022 | Collected Date: 2021 {: .meta }

Report Type: Annual Report {: .meta }

This report presents results from the Mental Health Client-Level Data (MH-CLD) and Mental Health Treatment Episode Data Set (MH-TEDS) for individuals receiving mental health services from state mental health systems in 2020, as well as selected trends in data collected from such individuals between 2015 and 2020.


</div>
{% endfor %}

{% for i in (1..13) %}
<div class="reports">

### National Survey Of Substance Abuse Treatment Services (N-SSATS)
Published Date: November 4, 2021 | Collected Date: 2020 {: .meta }

Report Type: Annual Report {: .meta }

This report presents results from the Mental Health Client-Level Data (MH-CLD) and Mental Health Treatment Episode Data Set (MH-TEDS) for individuals receiving mental health services from state mental health systems in 2020, as well as selected trends in data collected from such individuals between 2015 and 2020.

### 2020 National Mental Health Services Survey (N-MHSS)
Published Date: November 4, 2021 | Collected Date: 2020 {: .meta }

Report Type: Annual Report {: .meta }

This report presents results from the Mental Health Client-Level Data (MH-CLD) and Mental Health Treatment Episode Data Set (MH-TEDS) for individuals receiving mental health services from state mental health systems in 2020, as well as selected trends in data collected from such individuals between 2015 and 2020.
</div>
{% endfor %}