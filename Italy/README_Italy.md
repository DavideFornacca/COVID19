# Detail for Italy
In this folder, you will find a datasets of Italy at the second administrative level or ADM2 (referred as provinces).
The datasets include total accumulated COVID-19 infections, infections normalized by population size (100k residents), population size and densities, and air pollution metrics from ground stations and satellite observations (Sentinel-5). Unfortunately, data on COVID-19 fatalities are not available at this administrative level.  
 
#### Links to the datasets (.csv format)
- With accumulated COVID-19 data until 2020.03.23: `covid_air_italy_s5_20200323.csv` [[file]](covid_air_italy_s5_20200323.csv)
    
#### Columns description
- <ins>region</ins>: Name of region (ADM1)
- <ins>province</ins>: Name of province (ADM2)
- <ins>pop</ins>: Number of inhabitants (2019)
- <ins>pop_dens</ins>: Number of inhabitants per square kilometer
- <ins>cases</ins>: Number of COVID-19 infections (until 2020.03.23)
- <ins>cases_100k</ins>: Number of COVID-19 infections per 100,000 inhabitants
- <ins>CO_s5</ins>, <ins>NO2_s5</ins>, <ins>O3_s5</ins>, <ins>SO2_s5</ins>, <ins>Aerosol_s5</ins>, <ins>HCHO_s5</ins>: Tropospheric column measures of different pollutants in mol/m^2 (average of year 2019), derived from Sentinel-5 data. UV Aerosol Index is a qualitative index.
- <ins>PM25_gr</ins>, <ins>PM10_gr</ins>: Ground measures of PM 2.5 and PM 10 (ug/m3, averages 2013-2016)

#### Data sources
- **COVID-19**: Dipartimento della Protezione Civile, http://www.protezionecivile.it/
- **Population**: Istat – Italian National Institute of Statistics, http://dati.istat.it/
- **Air quality ground measures**: Ambient Air Quality Database, WHO, April 2018, https://www.who.int/airpollution/data/cities/en/
- **Air quality satellite measures**: European Space Agency, Sentinel-5 Atmospheric variables accessed and processed through the Google Earth Engine platform: https://developers.google.com/earthengine/datasets/tags/air-quality

#### Publications
All information can be found in the following paper:
Pansini R & Fornacca D, 2020. _Initial evidence of higher morbidity and mortality due to SARS-CoV-2 in regions with lower air quality_, medRxiv, https://doi.org/10.1101/2020.04.04.20053595. Available at https://www.medrxiv.org/content/10.1101/2020.04.04.20053595v2

