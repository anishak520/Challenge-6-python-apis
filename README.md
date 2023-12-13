# Challenge-6-python-apis
Showcase skills using python requests, APIs, and JSON traversals to answer a fundamental question: "What is the weather like as we approach the equator?

#Methods

##Part 1: WeatherPy
Create a Python script to visualise the weather of over 500 cities of varying distances from the equator.

Generate random geographic coordinates and find the nearest city to each latitude and longitude combination using the citipy Python library.
Next, the OpenWeatherMap API is used to retrieve waether data for each city.
Create a series of scatter plots to display the following relationships:
Latitude vs. Temperature
Latitude vs. Humidity
Latitude vs. Cloudiness
Latitude vs. Wind Speed
Separate the plots above into Northern and Southern hemispheres, then calculate the linear regression for each.
Linear regression is used to prove how the weather changes (or doesn't) depending on proximity to the equator.

##Part 2: VacationPy
Show how weather data can be used to plan future vacations using the Geoapify API and the geoViews Python library.

Create a map that displays a point for every city in the city_data_df DataFrame as shown in the following image. The size of the point indicates the humidity in each city.
Narrow down the city_data_df DataFrame to find your ideal weather condition.
The main objective is to limit the dataframe to 10-20 rows.
Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.
For each city, use the Geoapify API to find the first hotel located within 10,000 metres of your coordinates.
Add the hotel name and the country as additional information in the hover message for each city in the map 

###Resources
