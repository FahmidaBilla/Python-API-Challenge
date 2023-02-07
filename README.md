# Python-API-Challenge


Part 1: WeatherPy


In the first par, we created a Python script to visualize the weather of over 500 cities of varying distances from the equator and used the citipy Python library Links to an external site., the OpenWeatherMap API Links to an external site., and your problem-solving skills to create a representative model of weather across cities.

1. Build a series of scatter plot to show the following relationships:
    * Latitude vs. Temperature
    * Latitude vs. Humidity
    * Latitude vs. Cloudiness
    * Latitude vs. Wind Speed

2. Run linear regression on each relationship, only this time separating them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):
    * Northern Hemisphere - Temperature (F) vs. Latitude
    * Southern Hemisphere - Temperature (F) vs. Latitude
    * Northern Hemisphere - Humidity (%) vs. Latitude
    * Southern Hemisphere - Humidity (%) vs. Latitude
    * Northern Hemisphere - Cloudiness (%) vs. Latitude
    * Southern Hemisphere - Cloudiness (%) vs. Latitude
    * Northern Hemisphere - Wind Speed (mph) vs. Latitude
    * Southern Hemisphere - Wind Speed (mph) vs. Latitude

The sctter plot between Lattitude and Temperature showed a significant relationship between the two factors. As we move away from Equator the temperature drops. Scatter plots between the other factors with Latitude did not show any significant relationship.


![image](https://user-images.githubusercontent.com/120361200/217385173-3fea5748-f6dd-4c26-8736-1cbc1d410561.png)


The regression analysis between Northern Hemisphere Temp and Latitude showed, as some cities in the southern hemisphere move closer to the equator, temperatures rises.This proves a slight positive correlation between latitude and temperature in the southern hemisphere.
The regression line only explains 22% of the variability in the data.


 <img width="439" alt="Screenshot 2023-02-07 at 5 47 50 PM" src="https://user-images.githubusercontent.com/120361200/217385152-51f03576-9bc5-49c3-8175-5c71b089dbff.png">




Part 2: VacationPy

1. For this part we created a map that displays the humidity for every city generated from Part I - WeatherPy.

2. Narrowed down the DataFrame to a specific weather condition, to get a . For example:

    * A max temperature lower than or equals to 85 degrees but higher than or equals to 65.
    * Wind speed less than 5 m/s.
    * Cloudiness lower than or equals to 30.

3. Used Geoapify API to find the first hotel for each city located within 10,000 meters of city coordinates.



<img width="1023" alt="Screenshot 2023-02-07 at 5 57 24 PM" src="https://user-images.githubusercontent.com/120361200/217386177-1389ad98-2cea-4daa-80f1-053157d4ed7b.png">



Plotted the hotels on the map with each pin containing the Hotel Name, City, and Country.


<img width="1046" alt="Screenshot 2023-02-07 at 5 58 01 PM" src="https://user-images.githubusercontent.com/120361200/217386211-c38ccaf3-e84a-4dec-b0bb-63081a019d15.png">


