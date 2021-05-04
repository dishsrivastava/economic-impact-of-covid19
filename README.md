# economic-impact-of-covid19

### COVID-19’s Impact on the U.S. Economy 

Our project goal is to examine and understand the impact of COVID-19 on integral aspects of the U.S. economy such as GDP and Unemployment Rates; we chose these parameters as they are often used by economists to measure the current state of an economy. 

We have first gathered COVID-19 health data recorded daily by the U.S. Center for Disease Control to understand which months of the pandemic faced the highest number of new cases and deaths. We utilized R to wrangle this data into monthly, national data and created bar plots to help us visualize the peaks and troughs in the pandemic timeline beginning with Jan ‘20 through Mar ‘21. 

To study unemployment rates, we gathered Labor Force Statistics from the Current Population Survey Dataset from the U.S. Bureau of Labor Statistics. This dataset helped us understand the shifts in unemployment rates and the 1-monthly change in rates from Jan ‘20 to Mar ‘21. We mapped a timeline of the increase/decrease in cases and deaths along with the change in unemployment rates in order to infer a correlation. In creating these line charts, we calculated new cases and deaths as a proportional of the total (from Jan ‘20 to Mar ‘21) in order to place all three variables (unemployment rates, new cases, and deaths) on one axis. 

In order to further understand economic impacts in specific regions of the U.S., we have focused our GDP analysis on four states with contrasting population sizes and responses to the pandemic. We specifically examined California (strong response to the pandemic, large population size), Texas (relaxed response to the pandemic, large population size), Rhode Island (strong response to the pandemic, small population size), and Utah (relaxed response to the pandemic, small population size). We also explored the GDP changes between various industries such as art, health, technical professions, real estate, and food to better understand which contributors to state GDP were impacted the most. In our analysis of GDP, we created an interactive map with data from 2019 and 2020 in order to compare pre and post pandemic GDP. We additionally created barplots that displayed the change in GDP from 2017 to 2020 for our four chosen states.

It has been saddening to study this data, quantifying the rise in cases and deaths and amount of individuals who lost their employment or seeing the downward slope of GDP, however, we hope our findings will help inform how government responses to the pandemic impacted local and state economies and the health of residents in their respective economy.

### Datasets and Resources: 
[United States COVID-19 Cases and Deaths by State over Time Dataset](https://data.cdc.gov/Case-Surveillance/United-States-COVID-19-Cases-and-Deaths-by-State-o/9mfq-cb36) from the U.S. Center for Disease Control and Prevention.

[Labor Force Statistics from the Current Population Survey Dataset](https://beta.bls.gov/dataViewer/view/timeseries/LNS14000000;jsessionid=C58F68E9140FE3B07E16AFFA7F77786E) from the U.S. Bureau of Labor Statistics.  

[Gross Domestic Product by State, 4th Quarter 2020 and Annual 2020 (Preliminary)](https://www.bea.gov/data/gdp/gdp-state) from U.S. Bureau of Economic Analysis.

[Interactive Choropleth Maps](https://learn.r-journalism.com/en/mapping/census_maps/census-maps/) from R Journalism.

[R and Leaflet to create interactive choropleth maps](https://towardsdatascience.com/r-and-leaflet-to-create-interactive-choropleth-maps-8515ef83e275) from Towardsdatascience. 

[Filter with Date data](https://blog.exploratory.io/filter-with-date-function-ce8e84be680) from Exploratory.io. 

[R Markdown: The Definitive Guide](https://bookdown.org/yihui/rmarkdown) from Bookdown. 

[Lesson 2. Twitter Data in R Using Rtweet: Analyze and Download Twitter Data](https://www.earthdatascience.org/courses/earth-analytics/get-data-using-apis/use-twitter-api-r/) from EarthLab. 

[How to Generate Word Clouds in R](https://towardsdatascience.com/create-a-word-cloud-with-r-bde3e7422e8a) from Towardsdatascience. 





