# python-api-challenge
I used Python library, the OpenWeatherMap API, and a little common sense to create a representative model of weather across world cities.

Part I - WeatherPy

I created a series of scatter plots to showcase the following relationships:

        Temperature (F) vs. Latitude
        Humidity (%) vs. Latitude
        Cloudiness (%) vs. Latitude
        Wind Speed (mph) vs. Latitude
 
 I ran linear regression on each relationship. This time, separated the plots into Northern Hemisphere (greater than or equal to 0 degrees  latitude) and Southern Hemisphere (less than 0 degrees latitude):

        Northern Hemisphere - Temperature (F) vs. Latitude
        Southern Hemisphere - Temperature (F) vs. Latitude
        Northern Hemisphere - Humidity (%) vs. Latitude
        Southern Hemisphere - Humidity (%) vs. Latitude
        Northern Hemisphere - Cloudiness (%) vs. Latitude
        Southern Hemisphere - Cloudiness (%) vs. Latitude
        Northern Hemisphere - Wind Speed (mph) vs. Latitude
        Southern Hemisphere - Wind Speed (mph) vs. Latitude

final notebook must:

Randomly select at least 500 unique (non-repeat) cities based on latitude and longitude.
Perform a weather check on each of the cities using a series of successive API calls.
Include a print log of each city as it's being processed with the city number and city name.
Save a CSV of all retrieved data and a PNG image for each scatter plot.

Part II - VacationPy

I used jupyter-gmaps and the Google Places API to create a heat map that displays the humidity for every city from Part I.
I used Google Places API to find the first hotel for each city located within 5000 meters of your coordinates.
I plotted the hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.
