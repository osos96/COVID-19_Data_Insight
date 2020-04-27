# COVID-19_Data_Insight
This is a Data analysis project part of the Data Scientist Program from DataInsight
<hr>

# Introduction to COVID-19
**Coronavirus** is a family of viruses that can cause illness, which can vary from *common cold* and *cough* to sometimes more severe disease. **Middle East Respiratory Syndrome (MERS-CoV)** and **Severe Acute Respiratory Syndrome (SARS-CoV)** were such severe cases with the world already has faced.<br>
**SARS-CoV-2 (n-coronavirus)** is the new virus of the coronavirus family, which first *discovered* in 2019, which has not been identified in humans before. It is a *contiguous* virus which started from **Wuhan** in **December 2019**. Which later declared as **Pandemic** by **WHO** due to high rate spreads throughout the world. Currently (on date 23rd of April 2020), this leads to a total of 189K+ Deaths across the globe, including *110K+ deaths* alone in *Europe*.<br>
Pandemic is spreading all over the world; it becomes more important to understand about this spread. This NoteBook is an effort to analyze the data of confirmed, deaths, and recovered cases over time. In this notebook, the main focus is to analyze the spread trend of this virus all over the world. 


### SOURSES: 
 - [WHO](https://www.who.int/emergencies/diseases/novel-coronavirus-2019)
 - [CDC](https://www.cdc.gov/coronavirus/2019-nCoV/index.html)
 - [Worldometers COVID-19 Tracker](https://www.worldometers.info/world-population/population-by-country/)
 - [COVID-19 Tracker by Johns Hopkins University](https://www.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6)


### Dataset 
- 2019 Novel Coronavirus COVID-19 (2019-nCoV) [Data Repository](https://github.com/CSSEGISandData/COVID-19) by Johns Hopkins CSSE
- This dataset is updated on daily basis by Johns Hopkins CSSE
    
    
- 2020 Educational and Population Global [Data Repository](http://data.uis.unesco.org/) by UNESCO UIS Statistics


- This dataset is updated on annual basis by UNESCO UIS Statistics
   
   
- 2020 World Population by country and population density by [Worldometer.info](https://www.worldometers.info/world-population/population-by-country/)
- This dataset is updated on monthly basis by Worldometers.info
<hr>



# Table of Content :


<hr>


* Introduction to COVID-19
* Installing Libraries
* Imports and Datasets
* Defining Functions Used
* Importing Datasets from Local files
* Exploring Imported Datasets
* Preprocessing of Datasets
    - Cleaning Educational Dataset and Educational Population
    - Exploring Cleaned Educational Datasets
    - Cleaning COVID-19 and World Population & Density Datasets
    - Exploring Cleaned COVID-19 Datasets
* Statistical Analysis of COVID-19 Dataset
    - Correlation Analysis
    - Ploting CDF for confirmed cases counts
    - Plotting PMF for categorical confirmed cases count through time
    - Plotting PMF for categorical death cases count through time
    - Plotting PMF for categorical recovered cases count through time
    - Plotting PMF for categorical active cases count through time
* General Data Analysis 
    - Latest Total counts on Global Scale
    - Latest Total counts on Continental Scale
    * Latest Total counts on National Scale
* Visualization on Map
    - Subsetting Data for map visualization using plotly_express
    - Animated Global Confirmed Cases count through time
    - Animated Global Death Cases count through time
    - Animated Global Recovered Cases count through time
    - Animated Global Active Cases count through time
    - Animated Global Spread through time
* Trend of Cases on Global Scale
    - Worldwide Analysis
    - International Analysis
    - Finding the least and most active countries
* Further Analysis on most and least active countries
    - United States National Trends
    - United Kingdom National Trends
    - People's Republic of China National Trends
    - Germany National Trends
* Exploring Mortality Rates
    - Finding most affected countries and most mortality rates
    - Visualizing rate of change of mortality rate through time
    - Exploring Mortality rate between Continents
    - Investigating countries with highest mortality rates
    - Visualizing rate of change of mortality rate through time for top countries
* Exploring Population density wrt confirmed cases
* Countries with the highest confirmed to population ratio
* Exploring Population density wrt confirmed cases
    - Exploring densities of countries with confirmed cases within IQR of 50%
* Exploring Population illiteracy rate wrt confirmed cases
    - Exploring the countries with the highest illiteracy rate
* Final Thoughts
