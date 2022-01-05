# Detail for 8 countries
In this folder, you will find a datasets of 8 countries at the second administrative level or ADM2 (referred as provinces in Italy, France, and Spain, counties in the US, prefectures of China, departments in France, LTLA/NHS in the UK, districts in Germany) and in some cases at the firts administrative level or ADM1 (regions in Italy, provinces in Iran).
The datasets include total accumulated COVID-19 data (infections, deaths, and mortality rates), COVID-19 data normalized by population size (100k residents), population size and densities, air pollution metrics from ground stations (China, Italy, and the US) and satellite observations (NASA), Z-scores and p-values results of Local Moran’s Bivariate statistic.    
 
#### Links to the datasets (.csv format)
- **China**, COVID-19 data updated until 2020-05-23: [`covid_air_CH_20200523.csv`](covid_air_CH_20200523.csv)
- **Germany**, COVID-19 data updated until 2020-05-25: [`covid_air_DE_20200525.csv`](covid_air_DE_20200525.csv)
- **France** (only deaths), COVID-19 data updated until 2020-05-22: [`covid_air_FR_20200522.csv`](covid_air_FR_20200522.csv)
- **Iran** (ADM1, only infections), COVID-19 data updated until 2020-03-22: [`covid_air_IRAN_20200322.csv`](covid_air_IRAN_20200322.csv)
- **Italy** (ADM2, infections), COVID-19 data updated until 2020-05-22: [`covid_air_IT_province_20200522.csv`](covid_air_IT_province_20200522.csv)
- **Italy** (ADM1, deaths), COVID-19 data updated until 2020-05-22: [`covid_air_IT_region_20200522.csv`](covid_air_IT_region_20200522.csv)
- **Spain** (Autonomous regions considered as provinces), COVID-19 data updated until 2020-05-02: [`covid_air_SPAIN_20200502.csv`](covid_air_SPAIN_20200502.csv)
- **UK**, COVID-19 data updated until 2020-05-30: [`covid_air_UK_20200530.csv`](covid_air_UK_20200530.csv)
- **USA**, COVID-19 data updated until 2020-05-21: [`covid_air_USA_20200521.csv`](covid_air_USA_20200521.csv)

#### Columns description
- <ins>province</ins>: ADM1, in some cases it may be region, state, or other
- <ins>prefecture</ins>: ADM2, in other cases province, department, district, or other
- <ins>pop</ins>: Number of inhabitants (census or estimates 2016-2020, according to country)
- <ins>pop_dens</ins>: Number of inhabitants per square kilometer
- <ins>cases</ins>: Number of COVID-19 infections
- <ins>cases_100k</ins>: Number of COVID-19 infections per 100,000 inhabitants
- <ins>deaths</ins>: Number of COVID-19 fatalities
- <ins>deaths_100k</ins>: Number of COVID-19 fatalities per 100.000 inhabitants
- <ins>mortality</ins>: deaths/cases*100
- <ins>PM25_gr</ins>, <ins>PM10_gr</ins>, <ins>CO_gr</ins>, <ins>NO2_gr</ins>, <ins>O3_gr</ins>, <ins>SO2_gr</ins>: Ground measures of different pollutants (AQI averages 2014, or μg/m3 averages 2013-2016, or μg/m3, ppm, ppb of 2019, according to country and pollutant)
- <ins>NO2_sat</ins>: 1996-2012 average of global 3-Year running mean ground-level NO2, ppb (average of the administrative unit's territory)
- <ins>PM25_sat</ins>: 1998-2016 average of global annual PM 2.5, μg/m3 (average of the administrative unit's territory)
- <ins>Z-score</ins>: Z-score of Local Moran’s Bivariate statistic (spatial clustering)
- <ins>p-value</ins>: p-value of Local Moran’s Bivariate statistic (spatial clustering)
- <ins>q-value</ins>: q-value of Local Moran’s Bivariate statistic (spatial clustering)

#### Data sources
For the complete list of data sources, see Table 1 in the original publication (https://doi.org/10.3390/atmos12060795)

#### Publications
All information can be found in the following papers:
- Pansini R & Fornacca D, 2021. Early Spread of COVID-19 in the Air-Polluted Regions of Eight Severely Affected Countries. _Atmosphere_ **12**(6): 795. https://doi.org/10.3390/atmos12060795
- Pansini R & Fornacca D, 2020. Initial Evidence of Higher Morbidity and Mortality Due to SARS-CoV-2 in Regions with Lower Air Quality. _medRxiv_. https://doi.org/10.1101/2020.04.04.20053595 (preprint)
