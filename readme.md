# Petrol Prices in NSW - A Shallow Dive
![](https://images.unsplash.com/photo-1560005262-823d9a06c851?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=701&q=80 | width=100)

![](https://gyazo.com/eb5c5741b6a9a16c692170a41a49c858.png | width=100)

# Description
This github repo contains all the necessary files and notebook to recreate the analysis performed in [my article](https://medium.com/@bienebonia/petrol-prices-in-nsw-a-shallow-dive-6fc01158c370)

# Motivation
- This project was made for the Data Scientist Nanodegree as a requirement for project 1. 
- Fuel prices have always been a point of interest for me and this is the perfect to do a shallow dive in the area and extract some useful insights.

# Installation
Please ensure the following packages are installed within your Python Environment:
- Pandas
- geopandas
- geoviews
- Plotly

# Notes
- The data import process (data_prep()) may take a long time due to the large amount of rows to be parsed (approx 1mil+)
- Plotly viz will  not load in Github/nbviwer, will need to download repo on PC and view (viz can be seen on article)


# Description of Files
### Files in Raw_Data e.g 'price_history_apri2019'
- Each file contains the monthly fuel data for NSW
- Data ranges from July 2018 to July 2020

### Files in GEO_DATA
- This folder contains the shapefiles required to produce the choropleth map to answer question 3.
- NSW_LOCALITY_POLYGON_SHP-GGDA2020.shp was used to produce the shapefile.

# Data Source
- Monthly fuel prices in NSW can be found [here](https://data.nsw.gov.au/data/dataset/fuel-check)
- NSW Suburb Shapefile used for this analysis can be found [here](https://data.gov.au/dataset/ds-dga-91e70237-d9d1-4719-a82f-e71b811154c6/distribution/dist-dga-5f5ca807-0586-4b93-87dd-891691985272/?q=)

# Results
## 1. How was petrol prices changed over time?
### Findings
- There has been a cylical nature to fuel prices across all fuel types.
- Interestingly circa April 2020 we saw the cheapest time to get fuel.
- Now we are seeing a steady increase in prices almost reaching 2019 levels.
- We did not see significant changes in prices between the weekdays.

## 2. Which vendors produced the cheapest P98 petrol?
### Findings
- Costco produced the cheapest fuel consistently throughout the whole period
- Coles Express and BP also showed consistent high fuel prices leading the pack.
- Choosing the correct brand will yield cost savings.

## 3. Where are the cheapest and most expensive suburbs for P98 fuel?
## Findings
- Suburbs north and east of Sydney CBD experienced higher than average fuel prices
- Inner west sydney contains small patches of suburbs where fuel is below average.
- Western and South Western Sydney saw greater occurances of below average prices.






