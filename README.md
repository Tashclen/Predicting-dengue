# Predicting-dengue
The World Health Organisation believes there are around 500 million cases of Dengue every year. Because dengue is carried by mosquitoes, the transmission dynamics are related to climate variables such as temperature and precipitation. Although the relationship to climate is complex, a growing number of scientists argue that climate change is likely to produce distributional shifts that will have significant public health implications worldwide. 

Governments and charities have therefore launch a competition to see if data science can help predict and understand its spread better. 
DrivenData is hosting a competition online to find the best MAE model result using data of two particular locations: San Juan in Puerto Rico and Iquitos in Peru.
https://www.drivendata.org/competitions/44/dengai-predicting-disease-spread/page/80/
DrivenData has collected its data from the US government website: https://dengueforecasting.noaa.gov/

There are 24 features given, 20 of which are climate features:
City and date indicators: 
city – City abbreviations: sj for San Juan and iq for Iquitos 
Station descriptions that are inside or near the city are listed here:
San Juan, Puerto Rico: RQW00011641; Lat = 18.4325; Long = -66.0108;
Elevation = 2.7; Start = 1956; End = 2015
Iquitos, Peru: PE000084377; Lat = -3.783; Long = -73.3; Elevation = 126; Start =
1973; End = 2015

year - Year given in yyyy format
weekofyear - Week given in nn (1-53) format
week_start_date – Date given in yyyy-mm-dd format

NOAA's GHCN daily climate data weather station measurements: 
station_max_temp_c – Maximum temperature 
station_min_temp_c – Minimum temperature 
station_avg_temp_c – Average temperature 
station_precip_mm – Total precipitation 
station_diur_temp_rng_c – Diurnal temperature range

PERSIANN satellite precipitation measurements (0.25x0.25 degree scale): 
precipitation_amt_mm – Total precipitation

NOAA's NCEP Climate Forecast System Reanalysis measurements (0.5x0.5 degree scale): 
reanalysis_sat_precip_amt_mm – Total precipitation 
reanalysis_dew_point_temp_k – Mean dew point temperature 
reanalysis_air_temp_k – Mean air temperature 
reanalysis_relative_humidity_percent – Mean relative humidity 
reanalysis_specific_humidity_g_per_kg – Mean specific humidity 
reanalysis_precip_amt_kg_per_m2 – Total precipitation 
reanalysis_max_air_temp_k – Maximum air temperature 
reanalysis_min_air_temp_k – Minimum air temperature 
reanalysis_avg_temp_k – Average air temperature 
reanalysis_tdtr_k – Diurnal temperature range

Satellite vegetation - Normalized difference vegetation index (NDVI) - NOAA's CDR Normalized Difference Vegetation Index (0.5x0.5 degree scale) measurements: 
ndvi_se – Pixel southeast of city centroid 
ndvi_sw – Pixel southwest of city centroid 
ndvi_ne – Pixel northeast of city centroid 
ndvi_nw – Pixel northwest of city centroid


1 EDA: Exploring and cleaning the files.

2 Pickle: Pickling the files ready to use for modelling.

3 Models: Various models.

