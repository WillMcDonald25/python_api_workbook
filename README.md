# python-api-challenge
 
Data's true power is its ability to definitively answer questions. So, let's take what you've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What is the weather like as we approach the equator?"


This activity is broken down into two deliverables, WeatherPy and VacationPy.

Part 1: WeatherPy
In this deliverable, I created a Python script to visualize the weather of over 500 cities of varying distances from the equator. I use problem-solving skills to create a representative model of weather across cities.

For this part, I use the WeatherPy.ipynb Jupyter notebook.

I used the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, I create a series of scatter plots to showcase the following relationships:

- Latitude vs. Temperature

- Latitude vs. Humidity

- Latitude vs. Cloudiness

- Latitude vs. Wind Speed

I then compute Linear Regression for Each Relationship
I separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude).

I create the following plots:

- Northern Hemisphere: Temperature vs. Latitude

- Southern Hemisphere: Temperature vs. Latitude

- Northern Hemisphere: Humidity vs. Latitude

- Southern Hemisphere: Humidity vs. Latitude

- Northern Hemisphere: Cloudiness vs. Latitude

- Southern Hemisphere: Cloudiness vs. Latitude

- Northern Hemisphere: Wind Speed vs. Latitude

- Southern Hemisphere: Wind Speed vs. Latitude


Part 2: VacationPy
In this deliverable, I use my weather data skills to plan future vacations. Also, I use Jupyter notebooks, the geoViews Python library, and the Geoapify API.

I complete the following tasks:

- I create a map that displays a point for every city in the city_data_df DataFrame. The size of the point should be the humidity in each city.

- Humidity map


