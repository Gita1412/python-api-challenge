# python-api-challenge

Part 1: WeatherPy

Requirement 1 : Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude
- Use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code.
- Create a series of scatter plots to showcase the following relationships:
  1. Latitude vs. Temperature
  2. Latitude vs. Humidity
  3. Latitude vs. Cloudiness
  4. Latitude vs. Wind Speed

Requirement 2 : Compute Linear Regression for Each Relationship
- Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude).
- Create a series of scatter plots. Be sure to include the linear regression line, the model's formula, and the r^2 values.
- create the following plots:
  1. Northern Hemisphere: Temperature vs. Latitude
  2. Southern Hemisphere: Temperature vs. Latitude
  3. Northern Hemisphere: Humidity vs. Latitude
  4. Southern Hemisphere: Humidity vs. Latitude
  5. Northern Hemisphere: Cloudiness vs. Latitude
  6. Southern Hemisphere: Cloudiness vs. Latitude
  7. Northern Hemisphere: Wind Speed vs. Latitude
  8. Southern Hemisphere: Wind Speed vs. Latitude
- Explain what the linear regression is modeling. Describe any relationships that can be noticed and any other findings.



Part 2: VacationPy

Requirement : use the Geoapify API and the geoViews Python library and employ your Python skills to create map visualizations.
Steps :
- Create a map that displays a point for every city in the city_data_df DataFrame. The size of the point should be the humidity in each city.
- Narrow down the city_data_df DataFrame to find your ideal weather condition. For example:
    - A max temperature lower than 27 degrees but higher than 21
    - Wind speed less than 4.5 m/s
    - Zero cloudiness
 - Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.
 - For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.
 - Add the hotel name and the country as additional information in the hover message for each city on the map.










