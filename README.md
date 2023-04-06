
# cuSpatial at GTC 2023

Monday, March 20, 8-8:50 am PT
Michael Wang (@isVoid) and Thomson Comer (@thomcom)

## Data
[National Address Database](https://www.transportation.gov/mission/open/gis/national-address-database/national-address-database-nad-disclaimer)

[NYC Taxi Zones Shapefile](https://d37ci6vzurychx.cloudfront.net/misc/taxi_zones.zip)

[NYC 2015 Taxi Pickups and Dropoffs](https://rapidsai-data.s3.us-east-2.amazonaws.com/viz-data/nyc_taxi.tar.gz)

## Notebook

The demo notebook `gtc-2023.ipynb` demonstrates using the integration of cudf, cuspatial,
and geopandas to read the above datasets and map real addresses to the coordinates of
taxi pickups in 2015.
