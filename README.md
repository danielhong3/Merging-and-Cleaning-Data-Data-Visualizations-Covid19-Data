# Merging-and-Cleaning-Data-Data-Visualizations-Covid19-Data
In this project, we are taking data from the US Census, NYT data team, and the Department of Homeland Security and investigating the amount of resources with respect to population in various parts of the US. This data includes number of hospital beds, population in each area, the population distribution by age, death rate, confirmed cases, and probable cases. The goal for this data investigation is to see what areas are at a highest risk and how well they're prepared for Covid19 based on their available resources.
# Analysis
<br/>
Using python, we parsed edited and merged all of these data sources and cleaned them up in order to get the data that we're most interested in. Using these, we obtained the following graphs centered around US Population, percentage of the population that is an at-risk demographic, that percentage and the available hospital beds, and the counties with the highest total population of elderly.
<br/>
# Data Visualization 
<br/>
![NumElderly](https://github.com/danielhong3/Merging-and-Cleaning-Data-Data-Visualizations-Covid19-Data/blob/master/NumberOfElderly.png)
<br/>
This graph details the counties with the highest number of elderly. It is important to take note of this since people over the age of 60 are at the highest risk of mortality if they contract Covid19. While this graph does not take into account total population, because it is the raw number of elderly, it provides information on how many hospital beds or respirators may be needed for potentially serious cases.
<br/>
![Percentage](https://github.com/danielhong3/Merging-and-Cleaning-Data-Data-Visualizations-Covid19-Data/blob/master/PerfPopUnder18Over60.png)
<br/>
<br/>
Next, we have a graph detailing the percentage of elderly (over 60) and young people (below 18) within each fo these counties. The size of the bubble is scaled to the number of hospital beds in these areas. There are few areas with both a large number of young and old people.
<br/>
<br/>
![PercentScaledBeds](https://github.com/danielhong3/Merging-and-Cleaning-Data-Data-Visualizations-Covid19-Data/blob/master/newplot%20(1).png)
<br/>
<br/>
This next plot is the same graph, but with hospital beds scaled to beds per 1000 people. Since both these populations are at-risk, this is a rough metric of how prepared these areas are.
<br/>
![HeatMap](https://github.com/danielhong3/Merging-and-Cleaning-Data-Data-Visualizations-Covid19-Data/blob/master/newplot%20(3).png)
<br/>
<br/>
Finally, this is a heat map of various variables. This tells us the relationship between variables such as death, hospital beds per 1000, and age. The higher the coorelation between each variable, the warmer the color. Colder colors indicate a low coorelation. Unfortunately this graph is cluttered from the sheet number of variables used to generate it. It is much more clear in the Jupiter Notebook.
<br/>
# Conclusion
In general, python is a powerful tool for creating interactive graphs to help us investigate the level of prepare areas have for Covid19 and what areas need more resources to support their at-risk populations
<br/>
# Data
https://github.com/CSSEGISandData/COVID-19
https://github.com/nytimes/covid-19-data
https://data.census.gov/cedsci/table?q=United%20States&g=0100000US,.050000&tid=ACSST5Y2018.S0101&hidePreview=false&vintage=2018&layer=VT_2018_050_00_PY_D1&cid=DP05_0001E&t=Populations%20and%20People
https://www.census.gov/geographies/reference-files/2018/demo/popest/2018-fips.html
https://hifld-geoplatform.opendata.arcgis.com/datasets/hospitals
