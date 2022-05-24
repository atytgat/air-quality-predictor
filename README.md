# Predicting the concentration of fine particles (PM2.5) in the air of Beijing.

A neural network is trained to predict the air-quality in Beijing based on the concentration of certain particles, the
temperature, precipitation, wind speed etc.

# Data
The dataset used contains hourly air pollutants data from 12 nationally controlled air-quality monitoring sites. The air-quality data are from the Beijing Municipal Environmental Monitoring Center. The meteorological data in each air-quality site are matched with the nearest weather station from the China Meteorological Administration. The time period is from March 1st, 2013 to February 28th, 2017 [2].

There are a total of 15 features used to predict the PM2.5 concentration
1. year: year of data Input Variable
2. month: month of data Input Variable
3. day: day of data Input Variable
4. hour: hour of data in this row Input Variable
5. SO2: SO2 concentration (ug/m3 ) Input Variable
6. NO2: NO2 concentration (ug/m3 ) Input Variable
7. CO: CO concentration (ug/m3 ) Input Variable
8. O3: O3 concentration (ug/m3 ) Input Variable
9. TEMP: temperature (degree Celsius)
10. PRES: pressure (hP a)
11. DEWP: dew point temperature (degree Celsius)
12. RAIN: precipitation (mm)
13. wd: wind direction
14. WSPM: wind speed (m/s)
15. station: id of the air-quality monitoring site
16. PM2.5: PM2.5 concentration (ug/m3 ) Output Variable
