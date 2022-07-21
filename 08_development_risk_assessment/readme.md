# Development of new oil fields

The production company GlavRosGosNeft needs to decide where to drill a new well. Collected characteristics of oil sample for wells: oil quality and volume of its reserves in three regions. The characteristics for each well in the region are already known. A model has been built to predict the volume of reserves in new wells. Wells with the highest estimated values were selected. The regions with the maximum total profit of the selected wells have been identified. A model has been built to determine the region where production will bring the greatest profit. Potential profits and risks were analyzed using Bootstrap technique.

## Structure of the report:

1. Review of data and  EDA
2. Data preprocessing
3. Model building
4. Test
5. Conclusion


## Columns:

The exploration data of the three regions are in the files:

- geo_data_0.csv
- geo_data_1.csv
- geo_data_2.csv

In each file

- id — the unique identifier of the well
- f0, f1, f2 — three features of dots (it doesn't matter what they mean, but the features are significant)
- product — the volume of reserves in the well (thousand barrels)

## Used libraries

- pandas
- numpy
- sklearn
- statmodels
- scipy
