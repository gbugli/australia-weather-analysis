# Australia Weather Analysis

### Introduction
Analysis of weather data is traditionally performed using complex physical models with a considerable number of variables that nonetheless provide fairly inaccurate predictions due to instability of the weather conditions. Thus, in this project we focused on the analysis of weather data to demonstrate that data science methods can be used to complement such complex models by testing hypotheses and training simple models on historical weather data that can possibly provide sufficiently accurate insights and forecasts over a short time period.

### Datasets
- [Australia Weather Data](https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package): contains about 10 years of daily weather data collected from multiple weather stations located across all Australia. Each row represents an observation of a weather station on a given day and location (features *Date* and *Location*) where the rainfall, evaporation, sunshine, strongest wind gust direction and speed, minimum and maximum temperature on the 24 hours have been recorded; moreover, two measurements at 9am and 3pm respectively, have been recorded for wind direction, wind speed, humidity, pressure, temperature and fraction of sky obscured by cloud.

- [Melbourne Daily Temperature](http://www.bom.gov.au/jsp/ncc/cdio/weatherData/av?p_nccObsCode=122&p_display_type=dailyDataFile&p_startYear=&p_c=&p_stn_num=086282): contains 51 years of daily maximum temperature measurements, from 1971 to 2021, collected from a weather station located near Melbourne Airport.

### Overview
In this project an analysis on weather data has been presented to address different type of questions related to temperature and precipitation.
The questions addressed in this work are:
1. **Is Australia getting hotter?** i.e. use Australian weather data to determine whether temperatures significantly increased over the years through hypothesis testing.
2. **Do locations differ based on frequency of precipitation?** i.e. assess the difference in frequency of precipitation between Australia’s major geographical areas across the 10 years.
3. **Can we effectively predict rain tomorrow using the data?** 
Overall, we have learnt that Australia is a country characterized by low precipitations and increas- ingly high temperatures, with an heterogeneous distribution in terms of weather conditions over its extent. In particular, we were able to assess with high significance that climate change on the city of Melbourne has brought substantial increases in temperatures between the periods of 1971-1999 and 2000-2021, which is likely to be reflective of the nation’s overall climate trend. Moreover, a significant difference in the frequency of precipitation is found between North, South, East and West regions across the 10 year period from 2008 to 2017. This is indeed confirmed in Question 3 where the geographical location of the city plays an important role in predicting future precipitations.

For a more detailed analysis refer to the notebook and report. 