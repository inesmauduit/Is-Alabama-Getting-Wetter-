# Is Alabama Getting Wetter? Temperature and Precipitation Trends Across Seasons (1900–2026)

## Group Members
- Ines Mauduit
- Sophie Zhou

## Scientific Question
Has Alabama's wet season (Jan–Mar) precipitation intensity changed over 125 years, 
and does warmer temperature correlate with heavier rainfall, consistent with the 
"wet gets wetter" climate theory?

## Hypothesis
We hypothesize that wet season (January–March) precipitation has increased over time, 
consistent with the "wet gets wetter" climate theory, while dry season (August–September) 
trends remain weaker or absent. We also hypothesize that warmer average temperatures 
correlate with higher precipitation during the wet season.

## Datasets
- [NOAA Climate at a Glance Statewide Time Series](https://www.ncei.noaa.gov/access/monitoring/climate-at-a-glance/statewide/time-series): 
provides monthly precipitation and average temperature data for Alabama from 1900 to 2026. 
Freely available and loadable as CSV directly into pandas.

- [US Drought Monitor Time Series](https://droughtmonitor.unl.edu/DmData/TimeSeries.aspx): 
provides Alabama drought severity and coverage index over time. Publicly available for download.

## Analysis Summary
We will load monthly precipitation and temperature data for Alabama into pandas and use 
groupby and resample operations to analyze seasonal trends.

- First, we will isolate the wet season months (January–March) and dry season months 
(August–September) and compute long-term trend lines for each to compare how rainfall 
has evolved differently across seasons.

- Second, we will compute precipitation anomalies relative to the 1900–2026 climatology 
using groupby and transform, then plot annual anomalies to identify decades of unusually 
high or low rainfall.

- Third, we will create a scatter plot of average temperature vs precipitation during the 
wet season to assess whether warmer years tend to be wetter, directly testing the 
"wet gets wetter" hypothesis with over a century of observations.

- Finally, we will assess the correlation between average monthly temperatures and average 
precipitation for the heavy rain season (1900–2026) in Alabama.

