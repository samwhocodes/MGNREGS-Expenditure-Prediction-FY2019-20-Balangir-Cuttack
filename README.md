# MGNREGS-Expenditure-Prediction-2019-2020
**Aproach_0** has used Area, Perimeter, Latitude and Longitude of the centroid for AC level boundary from QGIS to predict the expenditure across ACs in Balangir and Cuttack. 

**Aproach 1** is the aggregation of predictions at block level to calculate the AC level expenditure. It was the approach that worked for Balangir district as there wasn't any overlaps in block boundaries over AC, however it wasn't the case for Cuttack or in general for any other district. Also, the boundry for Census block is mostly different from revenue blocks.

**Aproach_Final** is the aggregation of predictions at village level to calculate the AC level expenditure. 

The GeoJson for village level boundaries were extracted from [here](https://github.com/datameet/indian_village_boundaries)

The shapefile for AC and District boundaries were extracted from [here](https://github.com/datameet/maps/tree/master/assembly-constituencies)

Block level and village data were extracted from [population enumeration](https://censusindia.gov.in/2011census/population_enumeration.html) data of 2011 census.
