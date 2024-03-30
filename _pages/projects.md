---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

The following are some visualizations/dashboards I've developed while at Poverty Solutions.

## Major Projects
### [Food Security in Michigan](https://food-security.fordschool.umich.edu/)
* Built using **ArcGIS** and **React**
* Developed for Michigan Department Health and Human Services (MDHHS)

### [Index of Deep Disadvantage](https://tableau.dsc.umich.edu/t/UM-Public/views/new_IDD_map_060223/MainDash?:embed_code_version=3&:embed=y&:loadOrderID=0&:display_spinner=no&:showAppBanner=false&:display_count=n&:showVizHome=n&:origin=viz_share_link)
* Built using **Tableau**
* Developed in support of the release of [_The Injustice of Place_](https://poverty.umich.edu/research-funding-opportunities/data-tools/understanding-communities-of-deep-disadvantage/) by Kathy Edin, Luke Shaefer, and Timothy Nelson

### [Michigan Poverty & Well-Being Map](https://poverty.umich.edu/research-funding-opportunities/data-tools/michigan-poverty-well-being-map/)
* Built using **Tableau**

## Minor Projects
Below are some minor projects I've worked on during my time at Poverty Solutions.

### [Auto Insurance Rates in Michigan (2019-2020)](http://www-personal.umich.edu/~sjubaed/michigan_autoinsurance.html)
* Built using **R Shiny**

### [Historical Poverty Rates in Detroit](http://www-personal.umich.edu/~sjubaed/Detroit_poverty_tracts.html)
* Built using **R Leaflet**

### [Percent of Detroiters Living Below 200% of Federal Poverty Line](http://www-personal.umich.edu/~sjubaed/Detroit_FPL_tracts.html)
* Built using **R Leaflet**

### Hardship Index
* Built using **R Leaflet**
* [standard tracts](http://www-personal.umich.edu/~sjubaed/MI_choropleth_hardship_Jubaed.html)
  * Constructed by standardizing select ACS variables to create z-scores and summing the result. The resulting index was then normalized to be between 0 and 100, with a higher value representing an area of greater need
  * Census tracts with a larger Hardship Index should be prioritized over those with a smaller Index
* [aggregated tracts](http://www-personal.umich.edu/~sjubaed/MI_choropleth_hardship_Jubaed_aggregated.html)
  * Aggregates smaller census tracts with an appropriate neighboring tract such that their combined population was >= 1200
  * Done to minimize dropped tracts
* Developed for [Center for Health & Research Transformation](https://chrt.org/) and MDHHS to help prioritize census tracts in Michigan to send community health workers

<!--
#{% include base_path %}

#{% for post in site.teaching reversed %}
#  {% include archive-single.html %}
#{% endfor %}
--->
