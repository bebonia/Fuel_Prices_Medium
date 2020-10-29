# Petrol Prices in NSW - A Shallow Dive

## Description
This github repo contains all the necessary files and notebook to recreate the analysis performed in [my article](https://medium.com/@bienebonia/petrol-prices-in-nsw-a-shallow-dive-6fc01158c370)

## Installation
Please ensure the following packages are installed within your Python Environment:
- Pandas
- geopandas
- geoviews
- Plotly

## Notes
- The data import process (data_prep()) may take a long time due to the large amount of rows to be parsed (approx 1mil+)
- Plotly viz will  not load in Github/nbviwer, will need to download repo on PC and view (viz can be seen on article)


## Business Understanding
Petrol will always be a cost tied to the operation of vehicles. 

The aim of this analysis to understand what drives the cost of petrol in NSW and identify factors to minimize this cost.

Speficially the questions we are looking to answer are:

- #### How was petrol prices changed over time in NSW?
- #### Which brand provides the cheapest P98 petrol?
- #### Where in NSW can we get the cheapest P98 petrol?

By answering the above three questions, a business can plan their strategy in minimizing the cost due to petrol in maintaining their vehicles.


#### Data Understanding
Data to answer the questions were obtained from a dataset provided by the NSW government called 'Fuel Check'.

The data provided  is split monthly from July 2020 to July 2018.

Each dataset is stored in a excel spreadsheet and contains the following columns:

| Column Name        | Description                                             |
|--------------------|---------------------------------------------------------|
| ServiceStationName | The name of the service station where the fuel was sold |
| Address            | The address where the service station is located        |
| Suburb             | The suburb where the service station is located         |
| Postcode           | The postcode where the service station is located       |
| Brand              | The brand of the service station                        |
| FuelCode           | Type of fuel sold                                       |
| PriceUpdatedDate   | The date and time which the price was recorded          |
| Price              | The price in cents of the fuel                          |




## Data Source
- Monthly fuel prices in NSW can be found [here](https://data.nsw.gov.au/data/dataset/fuel-check)
- NSW Suburb Shapefile used for this analysis can be found [here](https://data.gov.au/dataset/ds-dga-91e70237-d9d1-4719-a82f-e71b811154c6/distribution/dist-dga-5f5ca807-0586-4b93-87dd-891691985272/?q=)
