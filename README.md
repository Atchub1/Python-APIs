# What's the Weather Like?
## Background
Whether financial, political, or social -- data's true power lies in its ability to answer questions definitively. In this project I use Python requests, APIs, and JSON traversals to answer a fundamental question: "What's the weather like as we approach the equator?"

Now, I know what you may be thinking: "Duh. It gets hotter..."

But, if pressed, how could I prove it?


I have created a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, I utilized a simple Python library, the OpenWeatherMap API to create a representative model of weather across world cities.

I have included a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude


## Steps
1. Randomly select at least 500 unique (non-repeat) cities based on latitude and longitude.
1. Perform a weather check on each of the cities using a series of successive API calls.
1. Include a print log of each city as it's being processed with the city number and city name.
1. Create scatter plots to show relationship between Latitude and temperature, humidity, cloudiness, and wind speed.
1. Save both a CSV of all data retrieved and png images for each scatter plot.
1. Include a description of three observable trends
