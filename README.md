# python-api-challenge
Module Challenge week6
There are two parts to this project: 
**Part 01: WeatherPy**
In this deliverable, I created a Python script to visualise the weather of over 500 cities of varying distances from the equator. I used the **citipy Python library**and the **OpenWeatherMap API**here.

_Requirement 1_: Create Plots to Showcase the Relationship Between Weather Variables and Latitude
To fulfil the first requirement, use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, create a series of scatter plots to showcase the following relationships:
Latitude vs. Temperature/
Latitude vs. Humidity/
Latitude vs. Cloudiness/
Latitude vs. Wind Speed

_Requirement 2:_ Compute Linear Regression for Each Relationship
To fulfil the second requirement, compute the linear regression for each relationship. Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). This includes the following plots: Northern Hemisphere: Temperature (C) vs. Latitude/
Southern Hemisphere: Temperature (C) vs. Latitude/
Northern Hemisphere: Humidity (%) vs. Latitude/
Southern Hemisphere: Humidity (%) vs. Latitude/
Northern Hemisphere: Cloudiness (%) vs. Latitude/
Southern Hemisphere: Cloudiness (%) vs. Latitude/
Northern Hemisphere: Wind Speed (m/s) vs. Latitude/
Southern Hemisphere: Wind Speed (m/s) vs. Latitude

**Part 2: VacationPy**
Here I used a previously created CSV file, i.e. in part 01. Jupyter notebooks, the geoViews Python library, and the Geoapify API are used for this analysis. Weather conditions are filtered as the following conditions.
A max temperature lower than 27 degrees but higher than 21/
Wind speed less than 4.5 m/s/
Zero cloudiness
For each city, use the Geoapify API to find the first hotel located within 10,000 metres of your coordinates. Add the hotel name and the country as additional information in the hover message for each city.

