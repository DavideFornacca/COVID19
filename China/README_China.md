# Detail for China
In this folder, you will find datasets of China (including Hong Kong SAR, Macao SAR, and Taiwan) at the second administrative level or ADM2 (referred as prefectures or cities).
The datasets include total accumulated COVID-19 infections and fatalities as well as mortality rates (fatalities/infections), infections and fatalities normalized by population size (100k residents), population size and densities, and air pollution metrics from ground stations and satellite observations (Sentinel-5).

#### Links to the datasets (.csv format)
- With COVID-19 data accumulated until 2020.03.24: `covid_air_china_s5_20200324.csv` [[file]](covid_air_china_s5_20200324.csv)
- With COVID-19 data accumulated until 2020.05.23: `covid_air_china_s5_20200523.csv` [[file]](covid_air_china_s5_20200523.csv) DOI: 10.13140/RG.2.2.24152.72968
- With COVID-19 data accumulated until 2020.05.23 aggregated at provincial level: `covid_air_china_s5_20200523_province.csv` [[file]](covid_air_china_s5_20200523_province.csv)
    
#### Columns description
- <ins>province</ins>: Name of province (ADM1)
- <ins>prefecture</ins>: Name of prefecture/city (ADM2)
- <ins>pop</ins>: Number of inhabitants (estimates 2017)
- <ins>pop_dens</ins>: Number of inhabitants per square kilometer
- <ins>cases</ins>: Number of COVID-19 infections
- <ins>cases_100k</ins>: Number of COVID-19 infections per 100,000 inhabitants
- <ins>deaths</ins>: Number of COVID-19 fatalities
- <ins>deaths_100k</ins>: Number of COVID-19 fatalities per 100.000 inhabitants
- <ins>mortality</ins>: deaths/cases*100
- <ins>CO_s5</ins>, <ins>NO2_s5</ins>, <ins>O3_s5</ins>, <ins>SO2_s5</ins>, <ins>Aerosol_s5</ins>, <ins>HCHO_s5</ins>: Tropospheric column measures of different pollutants in mol/m^2 (average of year 2019), derived from Sentinel-5 data. UV Aerosol Index is a qualitative index.
- <ins>PM25_gr</ins>, <ins>PM10_gr</ins>, <ins>CO_gr</ins>, <ins>NO2_gr</ins>, <ins>O3_gr</ins>, <ins>SO2_gr</ins>: Ground measures of different pollutants (AQI averages 2014)

#### Data sources
- **COVID-19**: Chinese government health commission, through the DXY (DX Doctor) website. http://ncov.dxy.cn/ncovh5/view/en_pneumonia
- **Population**: Chinese provincial governments, available at https://www.citypopulation.de/
- **Air quality ground measures**: http://aqicn.org, data organized and made available on the University of Harvard Dataverse, https://dataverse.harvard.edu
- **Air quality satellite measures**: European Space Agency, Sentinel-5 Atmospheric variables accessed and processed through the Google Earth Engine platform: https://developers.google.com/earthengine/datasets/tags/air-quality

#### Publications
All information can be found in the following papers:
- Pansini R & Fornacca D, 2020. _COVID-19 higher morbidity and mortality in Chinese regions with lower air quality_, medRxiv, https://doi.org/10.1101/2020.05.28.20115832. Available at https://www.medrxiv.org/content/10.1101/2020.05.28.20115832v1
- Pansini R & Fornacca D, 2020. _Initial evidence of higher morbidity and mortality due to SARS-CoV-2 in regions with lower air quality_, medRxiv, https://doi.org/10.1101/2020.04.04.20053595. Available at https://www.medrxiv.org/content/10.1101/2020.04.04.20053595v2
