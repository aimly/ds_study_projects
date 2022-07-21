# Real estate market analysis

Research analysis and data preprocessing for a dataset with advertisements for the sale of apartments in St. Petersburg has been carried out. The influence of the area, ceilings, the number of rooms, the date of announcement on the prices of apartments in all the presented settlements and the center of St. Petersburg for the construction of an automated system for determining prices in order to avoid fraud and anomalies were revealed. Based on data from the Yandex.Real estate service, the market value of various types of real estate, typical parameters of apartments, depending on the distance from the center, was determined. Data preprocessing has been done. Added new data. Constructed histograms, boxplots, scatter diagrams.

## Structure of the report:

1. Review of data and EDA
2. Data preprocessing
3. Building and checking hypothesis
4. Conclusion


## Columns:

- airports_nearest - distance to the nearest airport in meters
- balcony — number of balconies
- ceiling_height - ceiling height
- cityCenters_nearest - distance to the city center in meters
- days_exposition - how many days the ad was placed (from publication to removal)
- first_day_exposition - publication date
- floor - floor
- floors_total - total floors in the building
- is_apartment - apartments (boolean)
- kitchen_area - kitchen area in square meters
- last_price - price at the time of unpublishing
- living_area - living area in square meters
- locality_name — name of the locality
- open_plan - open plan (boolean)
- parks_around3000 - number of parks within a 3 km radius
- parks_nearest - distance to the nearest park in meters
- ponds_around3000 - the number of ponds within a radius of 3 km
- ponds_nearest — distance to the nearest body of water in meters
- rooms - number of rooms
- studio - studio apartment (boolean)
- total_area - area of the apartment in square meters
- total_images - the number of photos of the apartment in the ad


## Used libraries

- Pandas
- Matplotlib
- sklearn
- urllib
- math
