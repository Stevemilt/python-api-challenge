# Python API - What's the Weather Like?

## Part I - WeatherPy
In this example, you'll be creating a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, you'll be utilizing a simple Python library, the OpenWeatherMap API, and a little common sense to create a representative model of weather across world cities. Your first requirement is to create a series of scatter plots to showcase the following relationships:

Temperature (F) vs. Latitude
Humidity (%) vs. Latitude
Cloudiness (%) vs. Latitude
Wind Speed (mph) vs. Latitude

After each plot add a sentence or too explaining what the code is and analyzing. Your second requirement is to run linear regression on each relationship, only this time separating them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

Northern Hemisphere - Temperature (F) vs. Latitude
Southern Hemisphere - Temperature (F) vs. Latitude
Northern Hemisphere - Humidity (%) vs. Latitude
Southern Hemisphere - Humidity (%) vs. Latitude
Northern Hemisphere - Cloudiness (%) vs. Latitude
Southern Hemisphere - Cloudiness (%) vs. Latitude
Northern Hemisphere - Wind Speed (mph) vs. Latitude
Southern Hemisphere - Wind Speed (mph) vs. Latitude

After each pair of plots explain what the linear regression is modeling such as any relationships you notice and any other analysis you may have.

## Part II - VacationPy
Now let's use your skills in working with weather data to plan future vacations. Use jupyter-gmaps and the Google Places API for this part of the assignment.

Note: Remember that any API usage beyond the $200 credit will be charged to your personal account. You can set quotas and limits to your daily requests to be sure you can't be charged. Check out Google Maps Platform Billing and Manage your cost of use for more information.

Note: if you having trouble displaying the maps try running jupyter nbextension enable --py gmaps in your environment and retry.

Create a heat map that displays the humidity for every city from the part I of the homework.

Narrow down the DataFrame to find your ideal weather condition. For example:

o A max temperature lower than 80 degrees but higher than 70.

o Wind speed less than 10 mph.

o Zero cloudiness.

o Drop any rows that don't contain all three conditions. You want to be sure the weather is ideal.

o Note: Feel free to adjust to your specifications but be sure to limit the number of rows returned by your API requests to a reasonable number.

Using Google Places API to find the first hotel for each city located within 5000 meters of your coordinates.

Plot the hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.
