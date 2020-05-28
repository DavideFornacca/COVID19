# Details for China
In this folder, you will find datasets of China (including Hong Kong SAR, Macao SAR, and Taiwan) at the second administrative level or ADM2 (referred as prefectures or cities).
The datasets include total COVID-19 infections and fatalities as well as mortality rates (fatalities/infections), infections and fatalities normalized by population size (100k residents), population size and densities, and air pollution metrics from ground stations and satellite observations (Sentinel-5).
</br>
**Links to the datasets (.csv format)**
- With COVID-19 data updated on 2020.03.24: `covid_air_china_s5_20200324.csv` [[file]](covid_air_china_s5_20200324.csv)
- With COVID-19 data updated on 2020.05.23: `covid_air_china_s5_20200523.csv` [[file]](covid_air_china_s5_20200523.csv)
    
**Columns description**
- <ins>province</ins>: Name of province (ADM1)
- <ins>prefecture</ins>: Name of prefecture/city (ADM2)
- <ins>pop</ins>: Number of inhabitants
- <ins>pop_dens</ins>: Number of inhabitants per square kilometer
- <ins>cases</ins>: Number of COVID-19 infections
- <ins>cases_100k</ins>: Number of COVID-19 infections per 100,000 inhabitants
- <ins>deaths</ins>: Number of COVID-19 fatalities
- <ins>deaths_100k</ins>: Number of COVID-19 fatalities per 100.000 inhabitants
- <ins>mortality</ins>: deaths/cases*100
- <ins>CO_s5</ins>, <ins>NO2_s5</ins>, <ins>O3_s5</ins>, <ins>SO2_s5</ins>, <ins>Aerosol_s5</ins>, <ins>HCHO_s5</ins>: Tropospheric column measures of different pollutants (average of year 2019), derived from Sentinel-5 data.
- <ins>PM25_gr</ins>, <ins>PM10_gr</ins>, <ins>CO_gr</ins>, <ins>NO2_gr</ins>, <ins>O3_gr</ins>, <ins>SO2_gr</ins>: Ground measures of different pollutants (averages 2017)

**Publications**  
All information can be found in the following paper:
Pansini R & Fornacca D, 2020. _Initial evidence of higher morbidity and mortality due to SARS-CoV-2 in regions with lower air quality_, medRxiv, https://doi.org/10.1101/2020.04.04.20053595. Available at https://www.medrxiv.org/content/10.1101/2020.04.04.20053595v2
