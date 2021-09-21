# Python-API-Challenge
WeatherPy and VacationPy challenges
WeatherPy:
The first requirement was to create a series of scatter plots to showcase the following relationships:

Temperature (F) vs. Latitude
Humidity (%) vs. Latitude
Cloudiness (%) vs. Latitude
Wind Speed (mph) vs. Latitude

After each plot, added a sentence or two explaining what the code is analyzing.
The second requirement was to run linear regression on each relationship. Separated the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

Northern Hemisphere - Temperature (F) vs. Latitude
Southern Hemisphere - Temperature (F) vs. Latitude
Northern Hemisphere - Humidity (%) vs. Latitude
Southern Hemisphere - Humidity (%) vs. Latitude
Northern Hemisphere - Cloudiness (%) vs. Latitude
Southern Hemisphere - Cloudiness (%) vs. Latitude
Northern Hemisphere - Wind Speed (mph) vs. Latitude
Southern Hemisphere - Wind Speed (mph) vs. Latitude

Explained what the linear regression is modeling. 
Final notebook includes:

Randomly selected at least 500 unique (non-repeat) cities based on latitude and longitude.
Performed a weather check on each of the cities using a series of successive API calls.
Included a print log of each city as it's being processed with the city number and city name.
Saved a CSV of all retrieved data and a PNG image for each scatter plot.

VacationPy:
Created a heat map that displays the humidity for every city from Part I.
Narrowed down the DataFrame to find ideal weather conditions:

A max temperature lower than 75 degrees but higher than 40.
Wind speed less than 20 mph.
20% cloudiness.
Dropped any rows that did't contain all three conditions. 
Used Google Places API to find the first hotel for each city located within 5000 meters of the coordinates.


Plotted the hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.
