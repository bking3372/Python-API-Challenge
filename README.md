# Weather and Vacation Analysis using APIs in Python

  
### Step 1:  Visualize the weather of 500+ cities across the world at varying distances from the equator.  

This analysis included:
  *  Creating a data set of over 500 randomly distributed world cities and gathering current weather information for each city using the
     Open Weather API
  *  Creating a series of scatter plots to showcase the following relationships:
       - Temperature vs Latitude
       - Humidity vs Latitude
       - Cloudiness vs Latitude
       - Wind Speed vs Latitude
  *  Running a linear regression on each relationship and separating the data by Northern Hemisphere and Souther Hemisphere; creating plots for each of the relationships (temperature, humidity, cloudiness, wind speed) for the cities in each hemisphere
     
Data observations:
  *  This analysis shows that temperatures are higher for cities that are closer to the equator and lower for those cities farther from the equator.  This is shown by the curvilinear relationship in the scatter plot. 
  
  ![Temp Image](https://github.com/bking3372/Weather-and-Vacation-Analysis/blob/master/WeatherPy/WorldCityTemperature.png)
  
  *  There is little to no relationship between the other weather variables (humidity, cloudiness, and wind speed) and a city's location with respect to the equator.  This is shown by scatter plots with no distinct patterns in the data.
  
  ![Humidity Image](https://github.com/bking3372/Weather-and-Vacation-Analysis/blob/master/WeatherPy/WorldCityHumidity.png)
  ![Cloud Image](https://github.com/bking3372/Weather-and-Vacation-Analysis/blob/master/WeatherPy/WorldCityCloudiness.png)
  ![Wind Image](https://github.com/bking3372/Weather-and-Vacation-Analysis/blob/master/WeatherPy/WorldCityWindSpeed.png)

 
### Step 2:  Using the cities in the data set from Step 1, plan a place to go on vacation.
 
 This analysis included:
   *  Creating a heat map that displays the humidity for every city in the data set
   *  Narrowing the data set to ideal weather specifications.  For me, this ideal weather is:
        - Temperature between 70 and 80
        - Humidity between 30 and 50
        - Less than 30% cloud cover
   *  For these "ideal weather" cities, finding the nearest hotel in each city using the Google Places API
   *  Plotting these cities in the original heat map with markers for each city and an info box with the city's name,
      country, and the hotel found for each city
 
