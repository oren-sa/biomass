# Recurrent biomass deficits

These rasters show recurrent biomass deficits in West Africa between 2015 and 2019.

The BiomassValue Rasters were downloaded from Action Contre la Faim's geosahel.info platform (http://80.69.76.253/Viewer.aspx?map=Analyse-Biomasse-Finale#) and show the total annual Dry Matter Productivity (Biomass) at a 1km resolution. The values are expressed in kg/ha. These rasters are built from VITO's PROBA-V DMP Product (https://land.copernicus.eu/global/products/dmp)

The neg_anomaly_count raster indicate the number of times during the 2015-2019 period that a pixel had an annual biomass production inferior to 80% of its long-term average. These anomalies are calculated from an archive from 1998 to 2019. For instance, a pixel with a value of 3 experienced 3 years during the 2015-2019 period where total production was under 80% of the long-term average. 

The neg_anomaly_count_severe raster follows the same logic, however the production threshold is lowered to 50%.
