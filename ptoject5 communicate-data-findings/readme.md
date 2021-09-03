# Bike Sharing data Analysis

## Dataset
Bike sharing systems are new generation of traditional bike rentals where whole process from membership,
rental and return back has become automatic.
Through these systems, user is able to easily rent a bike from a particular position and return back at another position.

Attribute Information:
There are 731 rows in the dataset with 11 columns, and different variable types like (int - float - object) but the most type are numeric.
instant: record index
dteday : date
season : season (1:springer, 2:summer, 3:fall, 4:winter)
yr : year (0: 2011, 1:2012)
mnth : month ( 1 to 12)
hr : hour (0 to 23)
holiday : weather day is holiday or not (extracted from [Web Link])
weekday : day of the week
workingday : if day is neither weekend nor holiday is 1, otherwise is 0.
weathersit :
1: Clear, Few clouds, Partly cloudy, Partly cloudy
2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
temp : Normalized temperature in Celsius. The values are derived via (t-tmin)/(tmax-tmin), tmin=-8, t_max=+39 (only in hourly scale)
atemp: Normalized feeling temperature in Celsius. The values are derived via (t-tmin)/(tmax-tmin), tmin=-16, t_max=+50 (only in hourly scale)
hum: Normalized humidity. The values are divided to 100 (max)
windspeed: Normalized wind speed. The values are divided to 67 (max)
casual: count of casual users
registered: count of registered users
cnt: count of total rental bikes including both casual and registered

The dataset can be found in (https://www.kaggle.com/lakshmi25npathi/bike-sharing-dataset),



## Summary of Findings

The main focus was on the number of bikers,
the most sesons bikers used bike sharing, tempreuture,seasons...
the average count of users in fall season is the greatest than the other, spring season is the lowest number of bikers...
the average count of users in 2012 is greater than the average count of users in 2011
The average count of users in June and September isthe most, and the lowest average count of users in January.

## Key Insights for Presentation

For the presentation, I focus on seasons, number of users, months, years, tempreature  

Afterwards, I introduce each of the categorical and namercal variables one by one.
I use the plot matrix of numeric features against categorical features. 
also I've made distributions between average count of users and season, year, month, days, weathersit
sure to use different color palettes for each quality variable to make sure it
is clear that they're different between plots.
