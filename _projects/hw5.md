---
name: Homework 5
tools: [Python, Altair, vega-lite]
description: Submission for HW5
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---

# Chart 1

<vegachart schema-url="{{ site.baseurl }}/assets/json/chart1.json" style="width: 100%"></vegachart>

This chart displays the distribution of different license types in the dataset using a horizontal bar chart. 
The license types are arranged vertically on the y-axis, sorted from highest to lowest count, while the x-axis shows the number of licenses for each type. 
The data shows that the distribution of Detective Board licenses dominate with more than 5,000 licenses, followed by Cosmo licenses at around 3,000-4,000. 
Dental licenses come in third place with close to 1,000 licenses. The graph then drops significantly. The remaining license types, including professions such as Funeral and Embalmer, Dietetic and Nutrition, Design Firm, Massage Licensing Board, Home Inspector, and various others. 
All have relatively small counts of fewer than 100 licenses each. This shows that the vast majority of licenses are concentrated in just two professional categories, while numerous other professions are represented in much smaller numbers. 


# Chart 2

<vegachart schema-url="{{ site.baseurl }}/assets/json/chart2.json" style="width: 100%"></vegachart>

This second chart shows the number of licenses per county for a specific license type that can be selected from an interactive dropdown menu. "DESIGN FIRM" is the selected default from the dropdown, which displays various professional license types.  
The horizontal bar chart reveals that Cook County dominates with approximately 28 licenses for design firms, significantly outnumbering all other counties. The remaining counties shown all have very small counts of 1 or fewer licenses. 
Interestingly, the data includes some out-of-state counties, suggesting that the dataset may include licenses held by individuals or businesses registered in Illinois but located elsewhere, or it could indicate data quality issues with location entries. 
The chart effectively demonstrates the geographic concentration of design firm licenses within Illinois, with Cook County being the center of this professional activity.


<div class="left">
{% include elements/button.html link="https://github.com/UIUC-iSchool-DataViz/is445_data/raw/main/licenses_fall2022.csv" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/dhanviputtur/dhanviputtur.github.io/blob/master/python_notebooks/Workbook.ipynb" text="The Analysis" %}
</div>
