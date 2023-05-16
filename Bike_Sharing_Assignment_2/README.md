# Multiple Linear Regression - Bike Sharing
 This is a linear regression model for multiple indipendant variable build to find the factors that improve the bike rental demands.


## Table of Contents
* [Problem Statement](#Problem-Statement)
* [Business Goal](#Business-Goal)
* [Meta Information of the Variables](#Meta_Information_of_the_Variables)
* [Technologies used](#Technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## Problem Statement

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes. How well those variables describe the bike demands Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.

## Business Goal

Need to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

## Meta Information of the Variables:
- instant: record index
- dteday : date
- season : season (1:spring, 2:summer, 3:fall, 4:winter)
- yr : year (0: 2018, 1:2019)
- mnth : month ( 1 to 12)
- holiday : weather day is a holiday or not (extracted from http://dchr.dc.gov/page/holiday-schedule)
- weekday : day of the week
- workingday : if day is neither weekend nor holiday is 1, otherwise is 0.
- weathersit :
  - 1: Clear, Few clouds, Partly cloudy, Partly cloudy
  - 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
  - 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
  - 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
- temp : temperature in Celsius
- atemp: feeling temperature in Celsius
- hum: humidity
- windspeed: wind speed
- casual: count of casual users
- registered: count of registered users
- cnt: count of total rental bikes including both casual and registered




## Conclusions
- temp: Temperature has a significant impact on bike bookings, with an increase in temperature leading to a higher demand for rentals. This suggests that people are more inclined to rent bikes during warmer weather.

- weathersit: Certain weather conditions, such as mist with cloudy, mist with broken clouds, mist with few clouds, mist, light snow, light rain with thunderstorm and scattered clouds, and light rain with scattered clouds, may have a negative effect on bike bookings. These weather situations might deter people from renting bikes, potentially due to safety concerns or discomfort.

- windspeed: The speed of the wind is another factor that influences bike rental demand. An increase in windspeed is associated with a decrease in bookings, indicating that people may be less willing to ride bikes in windy conditions.

- seasons: Summer and winter seasons stand out as the periods with higher demand for rental bikes. This could be due to favorable weather conditions, vacation time, or seasonal activities that attract more people to outdoor biking.

- holidays: Bike rental demand tends to be lower during holidays. This could be because people have different activities and commitments during holidays, reducing their interest in renting bikes.

- Month of September (mnth_sep): September appears to be a month with a higher likelihood of increased bike rental demand. It could be influenced by factors such as pleasant weather, school holidays, or special events taking place during that month.

- Year (yr): The analysis shows a consistent increase in bike bookings each year. This indicates a growing popularity of bike rentals over time, possibly due to factors such as increased awareness, convenience, and changing transportation preferences.

Overall, the insights suggest that temperature, weather conditions, windspeed, seasons, holidays, specific months, and the year have a notable impact on bike rental demand. Businesses can utilize this information to optimize their operations, marketing strategies, and resource allocation to cater to the varying demand patterns throughout different seasons, weather conditions, and times of the year.


## Technologies Used
- Pandas
- numpy
- Matplotlib
- Seaborn
- Sckitlearn
- Statsmodel


## Acknowledgements

This Project was created by the knowledge and skill that i have learned through upgrad AI and ML masters program.

Thanks to Akhil and devesh, the instructors who took the PI sessions of Multiple linear regression.

Dataset credit : [1] Fanaee-T, Hadi, and Gama, Joao, "Event labeling combining ensemble detectors and background knowledge", Progress in Artificial Intelligence (2013): pp. 1-15, Springer Berlin Heidelberg, doi:10.1007/s13748-013-0040-3.



## Contact
Created by [@rmohamedbasith] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->