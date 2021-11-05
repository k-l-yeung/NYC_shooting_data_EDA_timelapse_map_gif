### <a id='overview'>1. Overview</a>

#### Motivation
- To explore factors that correlate with shooting incidents in New York City (NYC)
- To have **timelapse animated map of shooting incidents in NYC** between 2006 and 2020.  Results are shown below.
![per_precinct](https://user-images.githubusercontent.com/58142773/140527958-d7848fa3-7684-4344-bc21-7f5f85ee6432.gif)
![per_capita](https://user-images.githubusercontent.com/58142773/140527990-f5ec31d0-f3e4-48a5-ac4e-1fcdc59b74ec.gif)

#### Method
- NYPD historic shooting data, NYPD precinct data, and NYPD precinct shape file are combined to answer the below questions
- libraries such as pandas, pandasql, geopandas, and matplotlib are used to explore, clean, and combine data

Data sources
- [NYPD Shooting Incident Data (Historic)](https://catalog.data.gov/dataset/nypd-shooting-incident-data-historic)
  - [NYC police precinct data](https://johnkeefe.net/nyc-police-precinct-and-census-data)
  - [Data dictionary on NYC population features](https://www.documentcloud.org/documents/87708-pl94-171-1.html#document/p64)
  - [Precinct Shapefile, KMZ, GeoJSON](https://geodata.lib.berkeley.edu/catalog/nyu-2451-34568)
- Related: 
 - [NYPD arrest data (Historic)](https://data.cityofnewyork.us/Public-Safety/NYPD-Arrests-Data-Historic-/8h9b-rp9u)
 - Evidence of weather and crime: [1](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7310019/), [2](https://online.vwu.edu/news/environmental-studies/weather-and-crime/), [3](https://www.chicagotribune.com/data/ct-crime-heat-analysis-htmlstory.html), [4](https://www.nytimes.com/2018/09/21/upshot/a-rise-in-murder-lets-talk-about-the-weather.html)

#### Questions to be answered
- Is a particular day of that week that is more crime prone?
- Is a particular season (spring, summer, etc) that is more crime prone?
- Is there a particular time of the day that is more crime prone?
- Which specific combination of perpetrator-victim characteristics account for the highest percentage of the crime
- Which precinct is most crime prone?

### <a id='sam'>2. About the author: Kam Leung Yeung (Sam)</a>
* PhD in Cognitive Psychology, Iowa State University in Ames, Iowa, USA

**Social media**:
* [LinkedIn](https://www.linkedin.com/in/kamleungyeung/)
* [Google Scholar](https://scholar.google.com/citations?user=OwUmaN8AAAAJ)
* [GitHub](https://github.com/k-l-yeung)
* [Tableau](https://public.tableau.com/app/profile/kam.leung.yeung#!/)

