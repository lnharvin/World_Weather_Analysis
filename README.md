# World Weather Analysis

## Overview of Project
Add a weather description to the weather data already retrieved in this module. Have the beta testers use input statements to filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels. From the list of potential travel destinations, the beta tester will choose four cities to create a travel itinerary. Finally, using the Google Maps Directions API, you will create a travel route between the four cities as well as a marker layer map.

-   Deliverable 1: Retrieve Weather Data
-   Deliverable 2: Create a Customer Travel Destinations Map
-   Deliverable 3: Create a Travel Itinerary Map

### Purpose
Retrieve data from OpenWeatherMap API, store the data in a dataframe, plot the data using MatPlotLib and Google Maps and perform statistical analyses.

## Analysis and Challenges
The temperature preferences supplied in the analysis below was a minimum temperature of 75 degrees Fahrenheit and a maximum of 90 degrees Fahrenheit.

### Customer Travel Destinations Map
![Vacation Search](https://github.com/lnharvin/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)

### Travel Itinerary Map
![Travel Map](https://github.com/lnharvin/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)

### Travel Itinerary Weather Markers
![Cities of the Itinerary](https://github.com/lnharvin/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)

### Analysis of Outcomes Based on Goals
I was successful in generating random latitude and longitude coordinates from around the world, retrieving the information from an API request, collecting that information into a dataframe and cleaning weather data to ultimately produce a plot map with corresponding weather details and a near by hotel.

### Challenges and Difficulties Encountered
I ran into a couple of issues making API calls but I think that was once again due to Windows 11 compatibility issues. For the most part completing the challenge and overlooking the third deliverable is what took the longest to finish. 

## Results

- Two conclusions you can draw about the outcomes:
  - The closer you are to the equator the warmer the temperature will be.
  - A large portion of South American cities fitting the specified criteria are closer to the center and eastern portion of the continent.

- What are some limitations of this dataset?
  - Couldn't really find any limitations in the dataset that prevented analysis or caused issues with data cleaning.


*config file not included*
