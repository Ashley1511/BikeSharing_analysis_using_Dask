# Bike Sharing analysis using Dask

The objective is to rewrite the Bike Sharing analysis done in the Python for Statistical Programming subject using Dask data structures and ecosystem instead of plain pandas.


## DATASETS:

The datasets can be found on Kaggle's website : https://www.kaggle.com/marklvl/bike-sharing-dataset/home .

Both available csvs contain the following fields, except that the day.csv does not have the hr-column. 

- instant: Record index
- dteday: Date
- season: Season (1:springer, 2:summer, 3:fall, 4:winter)
- yr: Year (0: 2011, 1:2012)
- mnth: Month (1 to 12)
- hr: Hour (0 to 23)
- holiday: weather day is holiday or not (extracted from Holiday Schedule)
- weekday: Day of the week
- workingday: If day is neither weekend nor holiday is 1, otherwise is 0.
- weathersit: (extracted from Freemeteo)
    a: Clear, Few clouds, Partly cloudy, Partly cloudy
    b: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
    c: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
    d: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
- temp: Normalized temperature in Celsius. The values are derived via (t-t_min)/(t_max-t_min), t_min=-8, t_max=+39 (only in hourly scale)
- atemp: Normalized feeling temperature in Celsius. The values are derived via (t-t_min)/(t_max-t_min), t_min=-16, t_max=+50 (only in hourly scale)
- hum: Normalized humidity. The values are divided to 100 (max)
- windspeed: Normalized wind speed. The values are divided to 67 (max)
- casual: count of casual users
- registered: count of registered users
- cnt: count of total rental bikes including both casual and registered


# AUTHOR
    Camille Chauliac
    Student at IE University
    Master in Big data and Business analytics
