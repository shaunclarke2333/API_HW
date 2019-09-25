# Using matplotlib, citipy and weather APi to visualize weather data

I created a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, i used the citipy Python library, the OpenWeatherMap API and Matplotlib to create a representative model of weather across world cities.

I randomly selected at least 500 unique (non-repeat) cities based on latitude and longitude.
Performed a weather check on each of the cities using a series of successive API calls.
I also included a print log of each city as it's being processed with the city number and city name.
I also saved both a CSV of all data retrieved and png images for each scatter plot.

I built a series of scatter plots to showcase the following relationships:

Temperature (F) vs. Latitude
Humidity (%) vs. Latitude
Cloudiness (%) vs. Latitude
Wind Speed (mph) vs. Latitude





