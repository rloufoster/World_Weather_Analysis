# World_Weather_Analysis

## Project Overview

### Purpose

The purpose of this project was to collect and analyze worldwide weather data for PlanMyTrip to use to recommend ideal hotels based on clients' weather preferences, and to ultimately build an algorithm that will provide custom itineraries to clients on an ad hoc basis.

### Method

Create a Pandas DataFrame with 500 or more of the world’s unique cities and their weather data in real time. This process involved the collection, analysis, and visualization of the data.


### Collection of Data

1.) Use the NumPy module to generate more than 1,500 random latitudes and longitudes.

2.) Use the citipy module to list the nearest city to the latitudes and longitudes.

3.) Use the OpenWeatherMap API to request the current weather data from each unique city in your list.

4.) Parse the JSON data from the API request.

5.) Collect the following data from the JSON file and add it to a DataFrame:

   a. City, country, and date

   b. Latitude and longitude

   c. Maximum temperature

   d. Humidity

   e. Cloudiness

   f. Wind speed


### Exploratory Analysis with Visualization

1. Create scatter plots, determine correlations and create a series of heatmaps of the weather data for the following comparisons:

   a. Latitude versus temperature

   b. Latitude versus humidity

   c. Latitude versus cloudiness

   d. Latitude versus wind speed


### Visualize Travel Data

Create a heatmap with pop-up markers that can display information on specific cities based on a customer’s travel preferences. Complete these steps:

1. Filter the Pandas DataFrame based on user inputs for a minimum and maximum temperature.

2. Create a heatmap for the new DataFrame.

3. Find a hotel from the cities’ coordinates using Google’s Maps and Places API, and Search Nearby feature.

4. Store the name of the first hotel in the DataFrame.

5. Add pop-up markers to the heatmap that display information about the city, current maximum temperature, and a hotel in the city.


## Challenge Ask

The beta tests were positive on the PlanMyTrip app, and they asked that we build upon our success by making new modifications. We were asked to build an algorithm that would allow the client to input their individual preferences on weather conditions in order to narrow down the search for hotels in the desired areas. In addition, we would provide visual outputs with markers and travel directions between the cities that would be included in their itinerary packages. The sample provided filtered on maximum and mininimum acceptable temperatures, but the algorithm can now easily be adjusted to filter on other weather preferences.

