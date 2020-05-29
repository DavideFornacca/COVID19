# Details for the U.S.A.
In this folder, you will find a datasets of the U.S.A. at the second administrative level or ADM2 (referred as counties).
The datasets include total accumulated COVID-19 infections and fatalities, infections and fatalities normalized by population size (100k residents), population size and densities, and air pollution metrics from ground stations and satellite observations (Sentinel-5).  
 
#### Links to the datasets (.csv format)
- With accumulated COVID-19 data until 2020.03.29: `covid_air_usa_s5_20200329.csv` [[file]](covid_air_usa_s5_20200329.csv)
    
#### Columns description
- <ins>state</ins>: Name of state (ADM1)
- <ins>county</ins>: Name of county (ADM2)
- <ins>pop</ins>: Number of inhabitants (estimates 2018)
- <ins>pop_dens</ins>: Number of inhabitants per square kilometer
- <ins>cases</ins>: Number of COVID-19 infections (until 2020.03.29)
- <ins>cases_100k</ins>: Number of COVID-19 infections per 100,000 inhabitants
- <ins>deaths</ins>: Number of COVID-19 fatalities (until 2020.03.29)
- <ins>deaths_100k</ins>: Number of COVID-19 fatalities per 100.000 inhabitants
- <ins>mortality</ins>: deaths/cases*100
- <ins>CO_s5</ins>, <ins>NO2_s5</ins>, <ins>O3_s5</ins>, <ins>SO2_s5</ins>, <ins>Aerosol_s5</ins>, <ins>HCHO_s5</ins>: Tropospheric column measures of different pollutants in mol/m^2 (average of year 2019), derived from Sentinel-5 data. UV Aerosol Index is a qualitative index.
- <ins>PM25_gr</ins>, <ins>PM10_gr</ins>, <ins>CO_gr</ins>, <ins>NO2_gr</ins>, <ins>O3_gr</ins>, <ins>SO2_gr</ins>: Ground measures of different pollutants (ug/m3, ppm, or ppb;  2014)

#### Data sources
- **COVID-19**: The New York Times Github repository, https://github.com/nytimes/covid-19-data
- **Population**: U.S. Census Bureau, through ESRI ArcGIS data, https://www.arcgis.com/home/item.html?id=a00d6b6149b34ed3b833e10fb72ef47b
- **Air quality ground measures**: EPA – United States Environmental Protection Agency, https://www.epa.gov/outdoor-air-qualitydata
- **Air quality satellite measures**: European Space Agency, Sentinel-5 Atmospheric variables accessed and processed through the Google Earth Engine platform: https://developers.google.com/earthengine/datasets/tags/air-quality

#### Publications
All information can be found in the following paper:
Pansini R & Fornacca D, 2020. _Initial evidence of higher morbidity and mortality due to SARS-CoV-2 in regions with lower air quality_, medRxiv, https://doi.org/10.1101/2020.04.04.20053595. Available at https://www.medrxiv.org/content/10.1101/2020.04.04.20053595v2


